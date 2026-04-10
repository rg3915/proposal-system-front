<script lang="ts">
    import type { Album } from "../(data)/albums.js";
    import { cn } from "$lib/utils.js";

    let className: string | undefined | null = undefined;
    export let album: Album;
    export let aspectRatio: "portrait" | "square" = "square";
    export let width: number;
    export let height: number;
    export { className as class };
</script>

<div class={cn("space-y-3", className)} {...$$restProps}>
    <div class="overflow-hidden rounded-md">
        <img
            class={cn(
                "h-auto w-auto object-cover transition-all hover:scale-105",
                aspectRatio === "portrait" ? "aspect-[3/4]" : "aspect-square"
            )}
            {width}
            {height}
            src={album.cover}
            alt={album.name}
        />
    </div>
    <div class="space-y-1 text-sm">
        <h3 class="font-medium leading-none">{album.name}</h3>
        <p class="text-muted-foreground text-xs">{album.artist}</p>
    </div>
</div>