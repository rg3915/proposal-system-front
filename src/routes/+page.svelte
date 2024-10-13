<div
  class="hero"
  data-theme="dark"
>
  <nav class="container-fluid">
    <ul>
      <li>
        <a
          href="./"
          class="contrast"
        ><strong>LED Soft</strong></a>
      </li>
    </ul>
    <ul>
      <li>
        <details
          role="list"
          dir="rtl"
        >
          <summary
            aria-haspopup="listbox"
            role="link"
            class="contrast"
          >Theme</summary>
          <ul role="listbox">
            <li><a
                href="#"
                data-theme-switcher="auto"
              >Auto</a></li>
            <li><a
                href="#"
                data-theme-switcher="light"
              >Light</a></li>
            <li><a
                href="#"
                data-theme-switcher="dark"
              >Dark</a></li>
          </ul>
        </details>
      </li>
    </ul>
  </nav>
  <header class="container">
    <hgroup>
      <h1>LED Soft</h1>
      <p>Sistema de Orçamentos de LED</p>
    </hgroup>
    <p><a
        href="/orcamento_detail.html"
        role="button"
      >Experimente</a></p>
  </header>
</div>
<!-- ./ Hero -->

<!-- Main -->
<main class="container">
  <div class="grid">
    <section>
      <hgroup>
        <h2>Sistema de Orçamento de LED Completo para sua Empresa</h2>
        <p>Simplifique a Gestão de Produtos e Estoques de LED com Nosso Sistema Personalizado</p>
      </hgroup>

      <p>Aumente a eficiência de sua operação com o nosso sistema de orçamento de LED, que integra um catálogo de produtos completo e um controle de estoque em tempo real. Ideal para empresas que buscam automatizar processos, reduzir custos e melhorar a experiência de seus clientes.</p>

      <h3>Catálogo de Produtos Intuitivo</h3>

      <p>Tenha acesso a um catálogo detalhado com informações técnicas, fotos e preços atualizados. Com um clique, escolha os produtos que seus clientes precisam e monte orçamentos personalizados em segundos.</p>

      <figure>
        <img
          src="https://images.unsplash.com/photo-1608128947626-09e25f109c59"
          alt="Architecture"
        />
        <figcaption>
          Image from
          <a
            href="https://unsplash.com/photos/3Ijt7UkSBYE"
            target="_blank"
          >unsplash.com</a>
        </figcaption>
      </figure>

      <ul>
        <li>Produtos de iluminação LED de alta performance</li>
        <li>Descrições técnicas precisas e organizadas</li>
        <li>Atualização automática de preços e promoções</li>
      </ul>

      <h3>Orçamentos Personalizados em Segundos</h3>

      <p>Crie orçamentos completos e envie para seus clientes com rapidez e praticidade. Nosso sistema calcula tudo para você, incluindo impostos e descontos, garantindo total transparência e precisão.</p>

      <figure>
        <img
          src="https://images.unsplash.com/photo-1542744173-05336fcc7ad4"
          alt="Architecture"
        />
        <figcaption>
          Image from
          <a
            href="https://unsplash.com/photos/3Ijt7UkSBYE"
            target="_blank"
          >unsplash.com</a>
        </figcaption>
      </figure>

      <ul>
        <li>Elaboração rápida de orçamentos</li>
        <li>Envio direto por e-mail ou WhatsApp</li>
        <li>Histórico de cotações salvas</li>
      </ul>

      Transforme seu processo de vendas e estoque com nosso sistema de orçamento de LED.
    </section>

    <aside>
      <a
        href="#"
        aria-label="Example"
      ><img
          src="https://images.unsplash.com/photo-1526628953301-3e589a6a8b74"
          alt="Architecture"
        /></a>
      <p>
        <a href="#">Controle de Estoque Inteligente</a><br />
        <small>Nunca perca uma venda por falta de estoque! Gerencie suas entradas e saídas de produtos em tempo real, com alertas automáticos para repor mercadorias.</small>
      </p>

      <a
        href="#"
        aria-label="Example"
      ><img
          src="https://images.unsplash.com/photo-1551288049-bebda4e38f71"
          alt="Architecture"
        /></a>
      <p>
        <a href="#">Relatórios e Gestão Avançada</a><br />
        <small>Tenha acesso a relatórios completos de vendas, produtos mais vendidos e estoque. Tome decisões estratégicas baseadas em dados confiáveis e mantenha seu negócio sempre à frente da concorrência.</small>
      </p>
    </aside>
  </div>
</main>
<!-- ./ Main -->

<!-- Subscribe -->
<section aria-label="Subscribe example">
  <div class="container">
    <article>
      <hgroup>
        <h2>Experimente</h2>
        <p>Entre em contato agora e agende uma demonstração gratuita!</p>
      </hgroup>
      <form class="grid">
        <input
          type="text"
          id="firstname"
          name="firstname"
          placeholder="Nome"
          aria-label="Nome"
          required
        />
        <input
          type="email"
          id="email"
          name="email"
          placeholder="E-mail"
          aria-label="E-mail"
          required
        />
        <button type="submit">Enviar</button>
      </form>
    </article>
  </div>
</section>
<!-- ./ Subscribe -->

<!-- Footer -->
<footer class="container">
  <small>Built with <a href="https://picocss.com">Pico</a> •
    <a href="https://github.com/picocss/examples/tree/master/v1-company/">Source code</a></small>
</footer>
<!-- ./ Footer -->

<style>
/* Global CSS variables */
:root {
  --spacing-company: 3rem;
  --font-weight: 400;
  --border-radius: 0;
}

/* Typography */
h2,
h3,
hgroup> :last-child {
  font-weight: 200;
}

small {
  color: var(--muted-color);
}

.container {
    padding: 4rem 0;
}

/* Header */
.hero {
  background-color: #394046;
  background-image: url("https://images.unsplash.com/photo-1523961131990-5ea7c61b2107");
  background-position: center;
  background-size: cover;
}

header {
  padding: var(--spacing-company) 0;
}

header hgroup> :last-child {
  color: var(--h3-color);
}

header hgroup {
  margin-bottom: var(--spacing-company);
}

/* Nav */
summary[role="link"].contrast:is([aria-current], :hover, :active, :focus) {
  background-color: transparent;
  color: var(--contrast-hover);
}

/* Main */
@media (min-width: 992px) {
  main .grid {
    grid-column-gap: var(--spacing-company);
    grid-template-columns: auto 25%;
  }
}

form.grid {
  grid-row-gap: 0;
}

/* Aside nav */
aside img {
  margin-bottom: 0.25rem;
}

aside p {
  margin-bottom: var(--spacing-company);
  line-height: 1.25;
}
</style>