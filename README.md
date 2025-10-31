<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>Avaliador Escolar — Login</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="container">
      <aside class="sidebar" aria-label="Barra lateral">
        <div class="brand">
          <div class="logo">AE</div>
          <div>
            <h1>Avaliador Escolar</h1>
            <div class="small-muted">Protótipo visual</div>
          </div>
        </div>
        <nav class="nav" aria-label="Navegação principal">
          <a class="active" href="index.html"
            ><span class="material-icons" aria-hidden="true">login</span
            >Login</a
          >
          <a href="register.html"
            ><span class="material-icons" aria-hidden="true">person_add</span
            >Cadastro</a
          >
          <a href="dashboard.html"
            ><span class="material-icons" aria-hidden="true">dashboard</span
            >Dashboard</a
          >
          <a href="avaliacoes.html"
            ><span class="material-icons" aria-hidden="true">assignment</span
            >Avaliações</a
          >
          <a href="turmas.html"
            ><span class="material-icons" aria-hidden="true">group</span
            >Turmas</a
          >
          <a href="relatorios.html"
            ><span class="material-icons" aria-hidden="true">bar_chart</span
            >Relatórios</a
          >
          <a href="calendario.html"
            ><span class="material-icons" aria-hidden="true"
              >calendar_today</span
            >Calendário</a
          >
        </nav>
        <hr />
        <div class="small-muted" style="margin-top: 12px">Contatos</div>
        <div style="margin-top: 8px; font-size: 14px">help@avaliador.local</div>
      </aside>

      <main class="main" role="main">
        <div class="header">
          <div style="flex: 1">
            <h2 class="h2">Bem-vindo ao Avaliador Escolar</h2>
            <div class="p-muted">
              Acesse seu perfil para gerenciar avaliações, turmas e relatórios.
            </div>
          </div>
          <div class="header-right">
            <div class="small-muted">Versão protótipo</div>
          </div>
        </div>

        <div class="card" style="max-width: 720px; margin-bottom: 18px">
          <h3>Entrar</h3>
          <p class="small-muted">Insira suas credenciais</p>

          <form
            action="#"
            aria-label="Formulário de login"
            style="margin-top: 12px"
          >
            <div class="form-row">
              <input
                class="input"
                type="email"
                placeholder="E-mail"
                aria-label="E-mail"
                required
              />
              <select class="select" aria-label="Perfil">
                <option>Aluno</option>
                <option>Professor</option>
                <option>Administrador</option>
              </select>
            </div>
            <div class="form-row">
              <input
                class="input"
                type="password"
                placeholder="Senha"
                aria-label="Senha"
                required
              />
            </div>

            <div
              style="
                display: flex;
                gap: 12px;
                align-items: center;
                margin-top: 8px;
              "
            >
              <button class="btn" type="submit">Entrar</button>
              <a class="secondary btn" href="register.html" role="button"
                >Criar conta</a
              >
              <a href="#" class="small-muted" style="margin-left: auto"
                >Esqueci a senha</a
              >
            </div>
          </form>
        </div>

        <div class="columns">
          <div class="card">
            <h3 class="h2">Demonstração</h3>
            <p class="p-muted">
              Neste protótipo, navegue pelas páginas para visualizar layouts de
              cada funcionalidade.
            </p>
            <ul style="margin-top: 12px">
              <li>Perfis separados (Aluno / Professor / Admin)</li>
              <li>Gerenciamento de avaliações e turmas</li>
              <li>Relatórios com gráficos e exportação (placeholder)</li>
            </ul>
          </div>

          <aside class="card">
            <h3 class="h2">Atalhos</h3>
            <div style="margin-top: 8px">
              <a href="dashboard.html" class="tag info">Ir para Dashboard</a>
              <div style="height: 10px"></div>
              <a href="calendario.html" class="tag">Calendário</a>
            </div>
          </aside>
        </div>
      </main>
    </div>
  </body>
</html>
