# Projeto Site Advocacia em Html, Css e Js




https://user-images.githubusercontent.com/33934341/201348499-185816ae-4ce9-4edc-b976-f49ce664f296.mp4




```python
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pearson Hardman</title>
  <link rel="shortcut icon" href="img/favicon.ico" type="image/x-icon" />
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap"
    rel="stylesheet" />
  <!-- Bootstrap Icons -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css" />
  <!-- Estilos -->
  <link rel="stylesheet" href="css/styles.css" />
  <!-- Scripts -->
  <script src="js/scripts.js" defer></script>
</head>
```
![01](https://user-images.githubusercontent.com/33934341/201345252-807e55da-a281-472c-8122-63fef92f8ccf.png)

```python
  <!-- Cabeçalho e Banner -->
  <header id="header">
    <div id="inner-header">
      <h2 id="brand">Person Hardman</h2>
      <nav id="navbar">
        <a href="#header">Inicio</a>
        <a href="#expertise-areas">Serviços</a>
        <a href="#about">Sobre</a>
        <a href="#team">Time</a>
        <a href="#contact">Contato</a>
      </nav>
      <!-- Menu Mobile -->
      <i class="bi bi-list" id="menu"></i>
      <nav id="mobile-navbar">
        <i class="bi bi-x-lg" id="close-menu"></i>
        <a href="#header">Inicio</a>
        <a href="#expertise-areas">Serviços</a>
        <a href="#about">Sobre</a>
        <a href="#team">Time</a>
        <a href="#contact">Contato</a>
      </nav>
    </div>
  ```
  ![02](https://user-images.githubusercontent.com/33934341/201345643-a99c10b0-ff69-4234-ba91-e027c8a1aacc.png)

```python
  <!-- Areas de Atuação -->
  <main id="expertise-areas" class="text-image-section">
    <div id="expertise-information" class="text-container">
      <p class="section-subtitle">Áreas de atuação</p>
      <h3 class="section-title">
        Nossos especialistas podem ajudar você em Direito Civil, Ambiental,
        Empresarial.
      </h3>
      <a href="#" class="btn">Saiba Mais</a>
    </div>
    <div id="expertise-image-container" class="image-container">
      <i class="bi bi-people"></i>
      <img src="img/employees_banner.jpg" alt="Advogados da Pearson Hardman" />
    </div>
    <div id="other-services">
      <div class="service">
        <img src="img/bank.jpg" alt="Banco" />
        <i class="bi bi-bank"></i>
        <div class="service-info">
          <h4>Bancos e Finanças pessoais</h4>

```
![01](https://user-images.githubusercontent.com/33934341/201346033-72d0754e-71b9-4ee7-a898-b895ba4ee4c3.png)

```python
  <!-- Sobre nós -->
  <section id="about">
    <div id="about-text">
      <p class="section-subtitle">Sobre nós</p>
      <h3 class="section-title">
        Uma empresa que tem o foco no cliente, aconselhando da melhor forma e
        conseguindo os melhores resultados
      </h3>
      <div class="about-description">
        <i class="bi bi-briefcase"></i>
        <div>
          <h4>Advogados atualizados</h4>
          <p>
            Nós promovemos treinamentos mensais a todos os nossos
            colaboradores
          </p>
        </div>
      </div>
      <div class="about-description">
        <i class="bi bi-book"></i>
        <div>
  ```
  ![02](https://user-images.githubusercontent.com/33934341/201346283-5fb49102-8780-4f8f-9f6e-c5aeddae681b.png)

```python
  <!-- Contato -->
  <section id="contact" class="text-image-section">
    <div id="contact-image-container" class="image-container">
      <img src="img/office.jpg" alt="Advogados do Escritorio">
    </div>
    <div id="contact-information" class="text-container">
      <i class="bi bi-envelope"></i>
      <p class="section-subtitle">Entre em contato</p>
      <form>
        <div class="form-control">
          <input type="text" name="name" id="name" placeholder="Nome">
          <input type="email" name="email" id="email" placeholder="E-mail">
        </div>
        <input type="text" name="phone" id="phone" placeholder="Telefone">
        <textarea name="message" id="message" placeholder="Sua mensagem"></textarea>
        <input type="submit" value="Enviar" class="btn">
      </form>
    </div>
  </section>
```
![03](https://user-images.githubusercontent.com/33934341/201346378-19a143fa-29e5-4da7-85c1-0b8347d72066.png)

List | Valor do exemplo 
--------- | ------ 
1 | Criação de todo o Corpo em Html 
2 | Estilização em Css 
3 | Transições e menus com Js 
4 | Conexão do Form com o Banco de dados (Em construção)


