# Desenvolvimento-interface
Repositório para visualização do trabalho proposto.
<!DOCTYPEhtml >
< html  lang =" pt-br " >
< cabeça >
    < meta  charset =" UTF-8 " >
    < meta  nome =" descrição " conteúdo ="" />
    < meta  name =" palavras-chave " conteúdo ="" />
    < meta  name =" autor " conteúdo =" Everton Andrade "/>
    < meta  http-equiv =" X-UA-Compatible " content =" IE=edge " >
    < meta  name =" janela de visualização " conteúdo =" largura=largura do dispositivo, escala inicial=1,0 " >

    < link  href =" https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css " rel =" folha de estilo " integridade =" sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD " crossorigin =" anônimo " >
    < link  rel =" folha de estilo " type =" text/css " href =" ./css/style.css " >

    < link  rel =" icon " href =" img/logo.png "/>
    < title > Game Mania </ title >
</ cabeça >
< corpo >
    < cabeçalho >
        < nav  class =" barra de navegação bg-faded " >
            < div  class =" container-fluid " >
                < a  class =" navbar-brand " href =" index.html " > < img  class =" img-logo " src =" img/logo.png " alt =" Logo " > </ a >
                < form  class =" d-flex " role =" search " >
                    < input  class =" form-control me-2 " type =" search " placeholder =" Olá, o que deseja? " aria-label =" Search " >
                    < botão  class =" lupa btn btn-sm btn-contorno-secundário " type =" botão " > < img  src =" img/lupa.png " alt =" Pesquisar " > </ botão >
                    < button  class =" btn btn-outline-success " type =" submit " > < a  href =" login.html " > Login </ a > </ button >
                </forma> _ _
            </div> _ _
            < div  id =" barra de menu " >
                <ul> _ _
                    < li > < a  href =" index.html " > Início </ a > </ li >
                    < li > < a  href =" # " > Catálogo </ a > </ li >
                    < li > < a  href =" # " > Promoções </ a > </ li >
                    < li > < a  href =" # " > Categoria </ a > </ li >
                </ul> _ _
            </div> _ _
          </nav> _ _
    </ cabeçalho >

    <principal> _ _
        < div  id =" banner-esquerda " class =" banner-home d-flex align-items-center " >
            < div  class =" container-fluid " >
                < div  class =" linha p-lg-5 " >
                    < div  id =" img-esq " class =" col-6 " > < img  src =" img/banner01.png " class =" img-fluid " alt =" banner-home " > </ div >
                    < div  id =" img-dir " class =" col-6 " > < img  src =" img/banner02.png " class =" img-fluid " alt =" banner-home " > </ div >
                </div> _ _
            </div> _ _
        </div> _ _

        < div  id =" banner-direita " class =" banner-home d-flex align-items-center " >
            < div  class =" container-fluid " >
                < div  class =" linha p-lg-5 " >
                    < div  id =" texto-esq " class =" col-6 " >
                        < seção  classe =" menu-texto " >
                            < h1 > Conheça mais dos nossos produtos </ h1 >
                            < p > Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut vel ex vel est fermentum rutrum. Duis scelerisque elit in sodales convallis. Aenean id fringilla nibh. Donec et neque eget turpis congue viverra. Pellentesque habitant morbi tristique senectus et netus et maleuada famas ac turpis egestas. Aliquam id nulla nec odio venenatis sagittis. Nulla facilisi. Nulla tincidunt bibendum ex, et viverra sapien tristique in. Nullam non mollis urna. In quis mauris eu dui convallis hendrerit vel nec velit. Ut quis ex nulla. Duis et turpis nec lacus viverra fringilla. Nulla mauris sem, accumsan ac purus eget, pellentesque sollicitudin enim. Donec placerat tempor ex viverra varius. < br > Nam auctor tincidunt odio. Mauris orci eros, molestie ac blandit in.</p> _ _
                        </ seção >
                    </div> _ _
                    < div  id =" texto-dir " class =" col-6 " >
                        < seção  classe =" menu-texto " >
                            < h1 > Equipamentos eletrônicos e suas especificações </ h1 >
                            < p > Ut diam nibh, sollicitudin ac tincidunt sed, placerat porttitor velit. Sed hendrerit erat mauris, ut iaculis mi imperdiet ut. Duis rhoncus enim rhoncus luctus lobortis. Aenean facilisis sempre leo a pretium. Mauris vel consectetur libero. Fusce sodales felis vitae lorem vulputate, vitae cursus nulla dictum. Integer ipsum eros, condimentum nec risus sit amet, iaculis faucibus quam. < br > Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Integer molestie volutpat ex, cursus sodales nisl iaculis id. Aliquam libero metus, maleuada et dui nec, consequat congue justo. Nam vestibulum quis ligula at hendrerit. Vivamus a molestie ex. Aliquam urna turpis, rutrum vel massa in, tincidunt congue eros. </p >
                        </ seção >
                    </div> _ _
                </div> _ _
            </div> _ _
        </div> _ _

        < div  id =" carouselExampleCaptions " class =" carousel slide " >
            < div  class =" indicadores-carrossel " >
              < button  type =" botão " data-bs-target =" #carouselExampleCaptions " data-bs-slide-to =" 0 " class =" active " aria-current =" true " aria-label =" Slide 1 " > < / botão >
              < button  type =" botão " data-bs-target =" #carouselExampleCaptions " data-bs-slide-to =" 1 " aria-label =" Slide 2 " > </ botão >
              < button  type =" botão " data-bs-target =" #carouselExampleCaptions " data-bs-slide-to =" 2 " aria-label =" Slide 3 " > </ botão >
            </div> _ _
            < div  class =" carousel-inner " >
              < div  class =" carousel-item active " >
                < img  src =" img/carousel01.jpg " class =" d-block w-100 " alt =" ... " >
                < div  class =" carousel-caption d-none d-md-block " >
                    < h5 > Controle sem fio Xbox One Elite </ h5 >
                    < p > Conheça mais da nova atualização dos controles do Xbox One. </p> _ _
                </div> _ _
            </div> _ _
            < div  class =" item carrossel " >
                < img  src =" img/carousel02.jpg " class =" d-block w-100 " alt =" ... " >
                < div  class =" carousel-caption d-none d-md-block " >
                    <h5> Dualshock 3 </h5> _ _ _
                    < p > Sucessor do aclamado e antigo Dualshock 2(PS2). </p> _ _
                </div> _ _
            </div> _ _
            < div  class =" item carrossel " >
                < img  src =" img/carousel03.jpg " class =" d-block w-100 " alt =" ... " >
                < div  class =" carousel-caption d-none d-md-block " >
                    <h5> Dualshock 4 </h5> _ _ _
                    < p > Controle com ótimo gerenciamento nas mãos dos gamers. </p> _ _
                </div> _ _
            </div> _ _
            </div> _ _
            < button  class =" carrossel-control-prev " type =" botão " data-bs-target =" #carouselExampleCaptions " data-bs-slide =" anterior " >
                < span  class =" carousel-control-prev-icon " aria-hidden =" true " > </ span >
                < span  class =" visualmente oculto " > Anterior </ span >
            </ botão >
            < button  class =" carrossel-control-next " type =" botão " data-bs-target =" #carouselExampleCaptions " data-bs-slide =" next " >
                < span  class =" carousel-control-next-icon " aria-hidden =" true " > </ span >
                < span  class =" visually-hidden " > Próximo </ span >
            </ botão >
        </div> _ _

    < br >

        < ul  class =" nav nav-tabs justifique-content-center " id =" myTab " role =" tablist " >
            < li  class =" nav-item " role =" apresentação " >
                < button  class =" nav-link active " id =" home-tab " data-bs-toggle =" tab " data-bs-target =" #home-tab-pane " type =" botão " role =" tab " aria-controls =" home-tab-pane " aria-selected =" true " > Novidades </ botão >
            </li> _ _
            < li  class =" nav-item " role =" apresentação " >
                < button  class =" nav-link " id =" profile-tab " data-bs-toggle =" tab " data-bs-target =" #profile-tab-pane " type =" botão " role =" tab " ária -controls =" profile-tab-pane " aria-selected =" false " > Mais vendidos </ botão >
            </li> _ _
            < li  class =" nav-item " role =" apresentação " >
                < button  class =" nav-link " id =" contact-tab " data-bs-toggle =" tab " data-bs-target =" #contact-tab-pane " type =" botão " role =" tab " ária -controls =" contact-tab-pane " aria-selected =" false " > Últimas unidades </ button >
            </li> _ _
        </ul> _ _
        < div  class =" tab-content " id =" myTabContent " >
            < div  class =" tab-pane fade show active " id =" home-tab-pane " role =" tabpanel " aria-labelledby =" home-tab " tabindex =" 0 " >
                
                < div  class =" vendido " >
                    < div  class =" card-group " data-bs-theme =" dark " >
                        < div  class =" cartão " >
                            < img  src =" img/card01.jpg " class =" card-img-top " alt =" Notebook " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Notebook lenovo </ h5 >
                            < p  class =" card-text " > Equipado com i5 de décima primeira geração, 12gb de RAM, 1tb de ROM, placa de vídeo dedicada (NVIDIA MX-110), tela de 15,6". < / p >
                            < p  class =" preço " > R$ 2.879,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                        < div  class =" cartão " >
                            < img  src =" img/card02.jpg " class =" card-img-top " alt =" Mouse da Apple " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Mouse Bluetooth </ h5 >
                            < p  class =" card-text " > Bluetooth, recarregável, sem fio e tem uma base com design otimizado para ser movimentada suavemente pela mesa, bateria dura cerca de um mês. </p> _ _
                            < p  class =" preço " > R$ 799,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                        < div  class =" cartão " >
                            < img  src =" img/card03.jpg " class =" card-img-top " alt =" Smartphone " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Sony Xperia Z7 </ h5 >
                            < p  class =" card-text " > 512gb de ROM, 8gb de RAM, GPU Adreno 615 (Snapdragon 8gen1), CPU A75, tela 6,67", Android 13, câmeras de 64 e 16MP. < / p >
                            < p  class =" preco " > R$ 2.399,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                    
                    </div> _ _
                </div> _ _

            </div> _ _

            < div  class =" tab-pane fade " id =" profile-tab-pane " role =" tabpanel " aria-labelledby =" profile-tab " tabindex =" 0 " >

                < div  class =" vendido " >
                    < div  class =" card-group " data-bs-theme =" dark " >
                        < div  class =" cartão " >
                            < img  src =" ./img/card04.jpg " class =" card-img-top " alt =" Xbox 360 " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Xbox 360 Slim </ h5 >
                            < p  class =" card-text " > 500gb de armazenamento interno, um controle xbox 360 wireless, cabo HDMI, 3 meses de live gold. </p> _ _
                            < p  class =" preço " > R$ 1.249,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                        < div  class =" cartão " >
                            < img  src =" ./img/card05.jpg " class =" card-img-top " alt =" PS One " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Playstation One </ h5 >
                            < p  class =" card-text " > Reviva suas memórias com esse console atemporal da Sony. </p> _ _
                            < p  class =" preço " > R$ 599,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                        < div  class =" cartão " >
                            < img  src =" ./img/card06.jpg " class =" card-img-top " alt =" Playstation Vita " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Playstation Vita </ ​​h5 >
                            < p  class =" card-text " > Portátil de última geração da Sony, 64gb de ROM. </p> _ _
                            < p  class =" preço " > R$ 1.299,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                    </div> _ _
                </div> _ _

            </div> _ _

            < div  class =" tab-pane fade " id =" contact-tab-pane " role =" tabpanel " aria-labelledby =" contact-tab " tabindex =" 0 " >

                < div  class =" vendido " >
                    < div  class =" card-group " data-bs-theme =" dark " >
                        < div  class =" cartão " >
                            < img  src =" ./img/card07.jpg " class =" card-img-top " alt =" PS4 " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Playstation 4 Slim </ h5 >
                            < p  class =" card-text " > Console de 1tb, acompanha 5 jogos: Gran Turismo 7, God of War: Ragnarok, Horizon Zero Dawn Forbidden West, Resident Evil 4 Remake e Grand Theft Auto V. < / p >
                            < p  class =" preço " > R$ 2.799,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                        < div  class =" cartão " >
                            < img  src =" ./img/card08.jpg " class =" card-img-top " alt =" PS2 " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Playstation 2 Super Slim </ h5 >
                            < p  class =" card-text " > Consola retro da sexta geração de videojogos. </p> _ _
                            < p  class =" preço " > R$ 699,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                        < div  class =" cartão " >
                            < img  src =" ./img/card09.jpg " class =" card-img-top " alt =" PS3 " >
                            < div  class =" corpo do cartão " >
                            < h5  class =" card-title " > Playstation 3 Slim </ h5 >
                            < p  class =" card-text " > Antecessor do aclamado PS4, 256gb de espaço interno. </p> _ _
                            < p  class =" preco " > R$ 2.399,99 </ p >
                            < a  href =" # " class =" btn btn-primary " > Comprar </ a >
                            </div> _ _
                        </div> _ _
                    </div> _ _
                </div> _ _
            </div> _ _

        </div> _ _  

    </principal> _ _

    < br >

    < rodapé >
        < div  class =" container " data-bs-theme =" dark " >
            < div  class =" linha " >
              < div  class =" col-xl-5 col-lg-4 col-md-6 " >
                <div> _ _
                  < h3 > < img  src =" img/logo-banner.png " alt =" Logo " > </ h3 >
                  < p > Jogo Mania | Sua diversão também é a nossa! </p> _ _
                  < p  id =" info-cnpj " > CNPJ XX.XXX.XXX/XXXX-XX - Todos os direitos reservados. </p> _ _
                  < p  id =" info-inrvl " > Preços e condições de pagamento exclusivos para compras via internet e podem variar na loja física. Os preços podem ser alterados sem aviso prévio conforme disponibilidade em estoque. A Game Mania, não é responsável por erros descritivos. As fotos contidas nesta página são meramente ilustrativas do produto e podem variar de acordo com o fornecedor/lote do fabricante. Vendas sujeitas à análise e confirmação de dados. </p> _ _


                </div> _ _
              </div> _ _
              < div  class =" col-xl-2 col-lg-2 col-md-6 " >
                < div  classe ="" >
                  < h5 > Links Rápidos </ h5 >
                  < ul  class =" list-unstyled " >
                    <li> _ _
                      < a  href =" index.html " class =" text-decoration-none " > Início </ a >
                    </li> _ _
                    <li> _ _
                      < a  href =" # " class =" text-decoration-none " > Sobre nós </ a >
                    </li> _ _
                    <li> _ _
                      < a  href =" # " class =" text-decoration-none " > Serviços </ a >
                    </li> _ _
                    <li> _ _
                      < a  href =" # " class =" text-decoration-none " > Contato </ a >
                    </li> _ _
                  </ul> _ _
                </div> _ _
              </div> _ _
              < div  class =" col-xl-2 col-lg-3 col-md-6 " >
                <div> _ _
                  < h5 > Endereço </ h5 >
                  < ul  class =" list-unstyled " >
                    <li> _ _
                        < a  href =" tel:5511999999999 " class =" text-decoration-none " > (11) 99999-9999 </ a >
                    </li> _ _
                    < br >
                    <li> _ _
                      < a  href =" mailto:loja.gamemania@gmail.com " class =" text-decoration-none " > loja.gamemania@gmail.com </ a >
                    </li> _ _
                    < br >
                    <li> _ _
                      < p > Rua 18 de Janeiro, nº 52, < br > Centro, São Paulo/SP < br > CEP XXXXX-XXX </ p >
                    </li> _ _
                  </ul> _ _
                </div> _ _
              </div> _ _
              < div  class =" col-xl-3 col-lg-2 col-md-6 " >
                <div> _ _
                  < h5 > Rede Social </ h5 >
                  < ul  class =" list-unstyled redes-sociais " >
                    < li  class =" rs-ícone " >
                        < a  href =" https://www.facebook.com/GameManiaLoja " > < img  src =" img/logo-face.png " alt =" Facebook " > </ a >
                    </li> _ _
                    < li  class =" rs-ícone " >
                        < a  href =" https://www.instagram.com/gamemanialoja " > < img  src =" img/logo-insta.png " alt =" Instagram " > </ a >
                    </li> _ _
                  </ul> _ _
                </div> _ _
              </div> _ _
            </div> _ _
            < div  class =" d-flex justify-content-center " >
              < div  class =" direitos autorais " >
                < p > Desenvolvido por < a  href =" https://github.com/Xinnot " target =" _blank " > Everton A. </ a > </ p >
              </div> _ _
            </div> _ _
          </div> _ _
    </ rodapé >

    < id do botão  =" voltar-topo " type =" botão " class =" btn btn-outline-primary " onclick =" topo() " > ⇡ </ botão >
</ corpo >
    < script  src =" https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js " integridade =" sha384 -w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN " crossorigin " anônimo " > </ script >
    < tipo de script  =" text/javascript " src =" ./js/script.js " > </ script >
</html> _ _
