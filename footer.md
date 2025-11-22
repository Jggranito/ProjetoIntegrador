## HTML

<footer class="row">
    <div class="container-fluid p-0">
        <div class="col-12 footer-container">
          <div class="col-12 footer-content">
            <div class="col-12 col-lg-6">
              <img src="images/index/logo.png" alt="">
              <p>Comida boa, bebida gelada e a melhor seleção de músicas para você soltar a voz.</p>
              <div class="icons" data-bs-target="blanck">
                <a href="https://www.facebook.com/botequimoke/" target="_blank">
                  <i class="bi bi-facebook"></i>
                </a>
                <a href="https://www.instagram.com/botequimoke/?hl=am-et" target="_blank">
                  <i class="bi bi-instagram"></i>
                </a>
                <a href="" target="_blank">
                  <i class="bi bi-whatsapp"></i>
                </a>
              </div>
            </div>
            <div class="col-12 col-lg-6 segunda-coluna">
              <div class="col-12 col-lg-6">
                <h3>Informações</h3>
                <p>Sobre-nós</p>
                <p>Eventos</p>
                <p>Contato</p>
              </div>
              <div class="col-12 col-lg-6">
                <h3>Contato</h3>
                <p>Rua Sá Viana 141 - Rio de Janeiro</p>
                <p>(21) 97279-8301</p>
                <p>Qui: 18h - 00h</p>
                <p>Sex - Sab: 17h - 01h</p>
                <p>Dom: 16h - 00h</p>
              </div>
            </div>
          </div>
          <span class="row line footer-line"></span>
          <div class="col-12 ultima-linha">
            <p>© 2025 Botequim Okê. Todos os direitos reservados.</p>
          </div>
        </div>
    </div>
</footer>

## CSS

.footer-container {
  min-height: 360px;
  background-color: #ffffff;
  justify-items: center;
}
.footer-content {
  display: flex;
  flex-wrap: wrap;
  padding: 20px 50px;
}
.footer-content p{
  font-size: 13px;
  margin: 16px 0;
}
.segunda-coluna {
  display: flex;
  flex-wrap: wrap;
}
.segunda-coluna h3{
  margin-bottom: 40px;
}
.segunda-coluna p{
  margin: 10px 0;
}
.icons {
  display: flex;
  gap: 16px;
  font-size: 25px;
}
.footer-line {
  width: 95%;
}
.ultima-linha {
  margin-top: 40px;
  padding-bottom: 1px;
  text-align: center;
}