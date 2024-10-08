# ZelisoMB.github.io
copia img


    <!DOCTYPE html>
    <html lang="en">
    
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
            integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
            crossorigin="anonymous"></script>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
            integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
        <style>
            .padding-0{
                padding: 0;
            }
            .padding-0 button{
                padding: 0;
            }
            /* inicio-menu */
            .container-header {
                width: 100%;
                display: flex;
                padding: 2px 10px;
                justify-content: center;
                align-items: center;
                background: #DE0100;
            }

    header.title {
        color: #FFF;
        font-size: 13.4px;
        font-weight: 600;
        text-transform: uppercase;
        justify-content: center;
        display: flex;
        align-items: center;
        text-align: center;
    }

    div.home {
        display: flex;
        justify-content: center;
        padding: 15px 10px;
    }

    .container-menu-mobile {
        display: none;
        justify-content: space-between;
        align-items: center;
    }

    div.menu-itens-mobile {
        padding: 15px 0 !important;
        display: inline-flex;
        justify-content: center;
        color: black;

    }

    div.cgo-img {
        margin: 0 40px 0 0;
    }

    div.menu-itens {
        padding: 15px 0 !important;
        display: flex;
        justify-content: space-between;
        color: black;
        align-items: center;
    }

    .menu-itens a {
        display: flex;
        font-weight: 500;
        text-decoration: none;
        color: black;
        transition: 0.5s;
        padding: 0;
        align-items: center;
    }

    .menu-itens a:hover {
        color: #DE0100;
    }

    .svg-what {
        width: 28px;
        height: 28px;
    }

    .btn-menu-itens {
        gap: 5px   ;
        border: none;
        background-color: #ffffff;
    }

    .btn-menu-itens:focus-visible,
    .btn-menu-itens:focus:active,
    .btn-menu-itens:active,
    .btn-menu-itens:focus,
    .btn-menu-itens:hover {
        padding: 0 !important;
        gap: 5px;
        display: flex;
        align-items: center;
        background-color: #ffffff;
        color: black;
        border: none;
        padding: 0;
        outline: none !important;
        box-shadow: none;
    }

    .btn-aluno {
        color: #FFF !important;
        display: flex;
        align-items: center;
        gap: 5px;
        padding: 10px 15px!important;
        margin: 0 0 0 40px;
    }

    .menu-mobile {
        padding: 0 !important;
        gap: 1rem;
        display: flex;
        flex-direction: column;
    }

    .mobile a {
        text-decoration: none;
        color: rgb(0, 0, 0);
        transition: 0.3s ease;
        display: flex;
        gap: 5px;
        font-size: 1.1rem;
        align-items: center;
        margin: 1rem 0 0 0;
    }
    .btn-menu-itens-canvas:focus-visible,
    .btn-menu-itens-canvas:focus:active,
    .btn-menu-itens-canvas:active,
    .btn-menu-itens-canvas:focus,
    .btn-menu-itens-canvas:hover,
    .btn-menu-itens-canvas{
        color: #000;
        background-color: #FFF;
        border: none;
        outline: none !important;
        box-shadow: none;
        padding: 0;
        font-size: 16px;
        font-style: normal;
        font-weight: 500;
    }
    .btn-mobile {
        background-color: rgb(255, 255, 255);
        border: none;
        display: none;
        /* botão oculto p/ telas>*/
    }
    .custom-offcanvas-header{
        padding:16px 16px 0;
    }
    .custom-offcanvas{
        width: 55%;
    }
    .offcanvas-body a {
        align-items: center;
        text-decoration: none;
        color: #000;
        display: flex;
        justify-content: end;
        font-size: 16px;
        font-style: normal;
        font-weight: 500;
    }
    .dropdown-alain-left{
        text-align: end;
    }

    .offcanvas-body-mobile {
        gap: 20px;
        display: flex;
        flex-direction: column;
    }
    .costum-dropdown-item{
        align-items: center;
        gap: 5px;
    }
    /* end-menu */
    /* inicio-banner */
    .main-banner-mobile {
        display: none;
    }

    .main-banner-mobile-px {
        width: 100%;
    }

    .main-banner {
        background: linear-gradient(90deg, #B20A0A 0%, #DE0100 25.95%, #DE0100 39.27%, #9C19AA 100%);
        flex-shrink: 0;
    }

    .main-banner-px {
        width: 100%;
    }
    /* end-banner */
    /* inicio-container-cateoria */
    .container-categoria {
        display: flex;
        width: 100%;
        flex-direction: column;
        align-items: center;
        padding: 20px 0;
    }

    .container-artigo {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    }

    .h2-title {
        margin:20px 0;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        font-size: 36px;
        font-style: normal;
        font-weight: 800;
    }
    .linha-bege{
        display: none;
        height: 1px;
        background-color: #E1E1E1;
        width: 100%;
    }
    .container-pesquisa-mobile {
        flex-direction: column !important;
        display: none !important;
    }
    /* end-container-cateoria */
    .btn-color-amarelo {
        border: #FFD338;
        background: #FFD338;
        color: black;
        font-size: 18px;
        font-weight: 700;
    }
    .btn-card-mobile{
            display: none !important;
    }
    .btn-color-amarelo:focus-visible,
    .btn-color-amarelo:focus:active,
    .btn-color-amarelo:active,
    .btn-color-amarelo:focus,
    .btn-color-amarelo:hover {
        outline: none !important;
        background-color: #FFD338;
        box-shadow: none;
        color: #958113;
    }

    .btn-card-amarelo:focus-visible,
    .btn-card-amarelo:focus:active,
    .btn-card-amarelo:active,
    .btn-card-amarelo:focus,
    .btn-card-amarelo:hover {
        outline: none !important;
        background-color: #FFD338;
        box-shadow: none;
        color: #958113;
    }
    .tr-alain-center td{
        font-weight: 600;
        padding: 5px;
        text-align: center;
    }
    .container-pesquisa {
        margin: 0 0 20px;
        display: flex;
    }

    .container-pesquisa-mobile {
        justify-content: center;
        display: flex;
    }

    .container-btn-todos-center {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .search-container {
        display: flex;
        align-items: center;
        display: flex;
        position: absolute;
        background: none;
        border: none;
        cursor: pointer;
    }

    .busca {
        background: #636363;
        width: 12%;
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 0 10px 10px 0;
    }

    .search-bar {
        border-radius: 10px 0px 0px 10px;
        border: 1px solid #636363;
        background: #F0F0F0;
        width: 100%;
        font-size: 16px;
        font-style: italic;
        font-weight: 600;
        padding: 10px;
    }

    .barra {
        background: transparent;
        border-radius: 10px 10px 10px 10px !important;
        display: flex;
        width: 46vw;
        justify-content: space-between;
        margin-left: 20px;
    }

    .lupa {
        width: 1.4rem;
    }
    /* end-container-cateoria */
    /* inicio-container-curso */
    .container-curso {
        display: flex;
        align-items: center;
        color: #FFF;
        border-radius: 10px;
        background: #DE0100;
        padding: 12px 20px;
    }

    .container-curso h3 {
        display: flex;
        align-items: center;
        gap: 5px;
        margin: 0;
        font-size: 25px;
    }
    /* inicio-container-center */
    .container-grid {
        gap: 20px;
        display: grid;
        overflow-x: hidden; /* Para esconder a barra de rolagem horizontal */
        grid-template-columns: 290px 290px 290px 290px 290px;
    }

    .container {
        display: flex;
        justify-content: center;
    }

    .container-center {
        justify-content: center;
        display: flex;
        align-items: center;
        max-height: 465px;
    }
    .card-text{
        font-size: 17px;
        font-style: normal;
        font-weight: 400;
    }
    div.card-edit {
        border-radius: 10px;
        width: 18rem;
        margin: 50px 0;
        color: #FFF;

    }
    .container-btn-card{
        display: flex;
        justify-content: space-between;
        position: absolute;
        z-index: 1000;
    }
    button.btn-movimentar-card{
        margin: 0 0 20px;
        background: unset;
        border: unset;
    }
    a.btn-card {
        gap: 10px;
        justify-content: center;
        align-items: center;
        display: flex;
        border: none !important;
        width: 100%;
        border-radius: 9.649px;
        background: #9616B1;
        font-size: 17.709px;
        font-weight: 700;
    }

    .btn-card-amarelo {
        border: none;
        display: flex;
        padding: 7px 30px;
        gap: 10px;
        border-radius: 5px;
        background: #FFD338;
        color: #000;
        text-align: center;
        font-size: 18px;
        font-weight: 700;
        margin: 40px;
    }

    div.card-body {
        border-radius: 7px;
        height: 420px;
        overflow: hidden;
        position: relative;
        flex-direction: column;
        display: flex;
        justify-content: end;
        padding: 0 1rem 1rem 1rem;
        background: linear-gradient(180deg, rgba(31, 31, 31, 0.00) 3.99%, rgba(31, 31, 31, 0.70) 31.83%, #1F1F1F 56.31%),
            url('img/Teacher working on laptop 1.png');   
    }

    .box-card {
        margin: 0 0 1rem;
        display: flex;
        justify-content: left;
        gap: 11px;
    }

    .text-box-card {
        border-radius: 7px;
        border: 1px #FFF solid;
        font-size: 10px;
        padding: 2px 5px;

    }

    .date-box-card {
        font-size: 10px;
        border-radius: 5px;
        background: rgba(255, 255, 255, 0.20);
        align-items: center;
        padding: 3px 5px;
        justify-content: center;
    }
    /* end-container-curso */
    @media (min-width: 1200px) and (max-width: 1400px) {
        header.title {
            font-size: 11.9px;
        }
        .btn-menu-itens {
        gap: 2px   ;
        }
        div.cgo-img {
            margin: 0 25px 0 0;
        }

        .btn-aluno {
            margin: 0 0 0 25px;
        }

        .busca {
            font-size: 14px;
            color: #FFF;
            width: 12%;
            padding: 7px;
        }

        .menu-itens a {
            font-size: 15px;
        }
    }

    @media (min-width: 992px) and (max-width: 1200px) {
        header.title {
            font-size: 10.9px;
            font-weight: 500;
        }
        .btn-menu-itens {
        gap: 1px   ;
        }
        .menu-itens a {
            font-size: 13px;
        }

        div.cgo-img {
            margin: 0 15px 0 0;
        }

        a.svg-what {
            width: 10px !important;
            height: 10px !important;
        }

        .btn-aluno {
            padding: 7px !important;
            margin: 0 0 0 15px;
        }

        .busca {
            font-size: 14px;
            color: #FFF;
            width: 14%;
        }
        .tr-alain-center td{
        font-weight: 500;
        padding: 5px;
        font-size: 14px;
    }
        .container-curso {
            padding: 8px 13px;
        }

        .btn-color-amarelo {
            font-size: 16px;
        }
    }

    @media only screen and (max-width: 1200px) {
    }

    @media only screen and (max-width: 1100px) {
        header.title {
            font-size: 9.8px;
            font-weight: 500;
        }

        .menu-itens a {
            font-size: 12px;
        }
    }

    @media only screen and (max-width: 992px) {
        div.cgo-img {
            margin: 0 0 0 0;
        }
        .menu-itens a {
            font-size: 10.4px;
            font-weight: 400;
        }
        .btn-menu-itens {
        gap: 0px   ;
        }
        .svg-what {
            width: 18px;
            height: 18px;
        }

        .h2-title {
            font-size: 32px;
        }

        div.cgo-img {
            margin: 0 0 0 0;
        }

        .btn-aluno {
            margin: 0 0 0 0;
            padding: 5px !important;
        }

        .busca {
            font-size: 10px;
            color: #FFF;
            width: 15%;
            gap: 3px;
        }

        .search-bar {
            font-size: 14px;
        }

        .lupa {
            width: 15px;
        }

        .container-curso {
            padding: 7px 13px;
        }

        h3.container-curso-h3 {
            font-size: 22px !important;
        }

        .btn-color-amarelo {
            font-size: 12px;
        }
        .tr-alain-center td{
        font-weight: 400;
        padding: 2px;
        font-size: 11.4px;
        }
        .btn-card-amarelo {
            font-size: 14px;
        }
    }

    @media only screen and (max-width: 950px) {
        .search-bar {
            font-size: 12px;
            font-weight: 500;
        }
    }

    @media only screen and (max-width: 830px) {

        .barra {
            width: 100%;
        }
    }

    @media only screen and (max-width: 768px) {

        .btn-mobile:focus-visible,
        .btn-mobile:focus:active,
        .btn-mobile:active,
        .btn-mobile:focus,
        .btn-mobile:hover,
        .btn-mobile {
            background-color: rgb(255, 255, 255);
            outline: none;
            border: none;
            display: flex;
            box-shadow: none;
            padding: 0;
            /* botão oculto p/ telas>*/
        }
        .home {
            padding: 20px 10px;
        }
        .btn-mobile {
            margin-left: 26px;
        }
        .tr-alain-center td{
            font-size: 13px;
            font-weight: 600;
        }
        .h2-title {
            margin: 0;
            font-size: 20px;
            font-weight: 800;
            line-height: 115%;
            /* 23px */
        }
        .linha-bege{
        display: flex;
        }
        .container-menu-mobile {
            display: flex;
        }

        .container-categoria {
            padding: 20px 0;
        }
        div.card-body {
        height: 400px;  
    }
        .container-artigo {
            gap: 20px;
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }
        .container-grid {
        overflow-x: auto; /* Para colocar a barra de rolagem */
        }
        .card-text{
        font-size: 15.3px;
        }
        a.btn-card{
        font-size: 14.5px;
        }
        .container-btn-card{
        display: none !important;
        }
        .btn-card-amarelo{
            display: none;
        }
        .btn-card-mobile{
            display: flex !important;
            width: fit-content;
            border-radius: 5px;
            font-size: 13.85px;
            font-weight: 700;
        }
        .container-center-mobile{
            display: flex;
            justify-content: center;
        }

        div.menu-itens {
            display: none;
        }

        .container-pesquisa {
            display: none;
        }

        header.title {
            font-size: 13px;
            font-weight: 600;
        }
        .svg-what{
            width: 28px;
            height: 28px;
        }
        .btn-color-amarelo {
            gap: 15px;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 10px 15px;
            border-radius: 5px;
            font-size: 13.85px;
        }

        .container-pesquisa-mobile {
            flex-direction: column !important;
            gap: 20px;
            display: flex !important;
        }

        .search-container-mobile {
            display: flex;
            position: unset;
        }

        .search-bar {
            padding: 10px;
        }

        .barra {
            margin: 0 !important;
        }

        .container-curso-h3 {
            border-radius: 10px !important;
            padding: 8px 10px;
            font-size: 13.85px;
            font-weight: 700;
            margin: 0;
        }

    }

    @media only screen and (max-width: 576px) {
        .main-banner {
            display: none;
        }

        .main-banner-mobile {
            display: flex;
        }

        .container-menu-mobile {
            align-items: center;
        }

        .btn-card-amarelo {
            padding: 15px 30px;
            border-radius: 50px;
            font-size: 13.85px;
            font-weight: 700;
        }

        .cgo-img {
            width: 111px;
        }
        .btn-aluno {
            padding: 10px 15px !important;
        }

        .btn-mobile {
            margin-left: 26px;
        }

        .container-pesquisa-mobile {
            flex-direction: column !important;
            display: flex;
        }

        .search-container-mobile {
            display: flex;
            position: unset;
        }
        .lupa {
            width: 16.171px;
            height: 16.171px;
        }

    }
    </style>
    </head>
    
    <body>
        <div class="container-header">
            <header class="title col-lg-8 col-sm-8 col-12">
                único site de cursos livres com certificado emitido por uma faculdade credenciada no mec. portaria ead nº
                499 de 08/07/2021
            </header>
        </div>
        <main>
            <div class="home">
                <div class="container-menu-mobile col-sm-8 col-12">
                    <div class="cgo-img">
                        <a href="#"><img src="/Logo CGO.jpg" alt="CGO"></a>
                    </div>

            <div class="d-flex align-items-center">
                <div>
                    <a href="#" class="btn btn-dark btn-aluno" role="button">
                        <svg xmlns="http://www.w3.org/2000/svg" class="svg-what" width="24" height="24"
                            viewBox="0 0 24 24" fill="none">
                            <mask id="mask0_4201_1497" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0"
                                y="0" width="24" height="24">
                                <rect x="0.265625" y="0.382812" width="23.2344" height="23.2344" fill="#D9D9D9" />
                            </mask>
                            <g mask="url(#mask0_4201_1497)">
                                <path
                                    d="M11.8848 22.165C10.723 21.0678 9.39191 20.2288 7.89136 19.6479C6.3908 19.067 4.81764 18.7766 3.17188 18.7766V8.12752C4.80151 8.12752 6.3666 8.42199 7.86715 9.01091C9.36771 9.59984 10.7069 10.451 11.8848 11.5643C13.0626 10.451 14.4018 9.59984 15.9024 9.01091C17.4029 8.42199 18.968 8.12752 20.5977 8.12752V18.7766C18.9358 18.7766 17.3586 19.067 15.8661 19.6479C14.3736 20.2288 13.0465 21.0678 11.8848 22.165ZM11.8848 9.09562C10.8199 9.09562 9.90823 8.71645 9.14989 7.95811C8.39154 7.19976 8.01237 6.28813 8.01237 5.22323C8.01237 4.15832 8.39154 3.24669 9.14989 2.48835C9.90823 1.73 10.8199 1.35083 11.8848 1.35083C12.9497 1.35083 13.8613 1.73 14.6196 2.48835C15.378 3.24669 15.7572 4.15832 15.7572 5.22323C15.7572 6.28813 15.378 7.19976 14.6196 7.95811C13.8613 8.71645 12.9497 9.09562 11.8848 9.09562Z"
                                    fill="white" />
                            </g>
                        </svg>
                        SOU ALUNO
                    </a>
                </div>

                <div>
                    <button class="btn btn-primary btn-mobile" type="button" data-bs-toggle="offcanvas"
                        data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">
                        <svg xmlns="http://www.w3.org/2000/svg" width="41" height="41" viewBox="0 0 41 41"
                            fill="none">
                            <mask id="mask0_4233_1573" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0"
                                y="0" width="41" height="41">
                                <rect x="0.507812" y="0.507812" width="39.9844" height="39.9844" fill="#D9D9D9" />
                            </mask>
                            <g mask="url(#mask0_4233_1573)">
                                <path
                                    d="M10 12.1699V8.83789H39.9883V12.1699H10ZM10 32.1621V28.8301H39.9883V32.1621H10ZM10 22.166V18.834H39.9883V22.166H10Z"
                                    fill="#1C1B1F" />
                            </g>
                        </svg>
                    </button>
                </div>
            </div>
            <div class="offcanvas offcanvas-end custom-offcanvas" tabindex="-1" id="offcanvasRight"
                aria-labelledby="offcanvasRightLabel">
                <div class="offcanvas-header custom-offcanvas-header">
                    <h5 id="offcanvasRightLabel"></h5>
                    <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                </div>
                <div class="offcanvas-body offcanvas-body-mobile">
                    <a href="#" class="menu-itens-a">INÍCIO</a>
                    <div class="linha-bege"></div>
                    <a href="#" class="menu-itens-a">CURSOS</a>
                    <div class="linha-bege"></div>
                    <a href="#" class="menu-itens-a">COMO FUNCIONA</a>
                    <div class="linha-bege"></div>
                    <a href="#" class="menu-itens-a">ATENDIMENTO<svg xmlns="http://www.w3.org/2000/svg" width="19" height="29" viewBox="0 0 19 29" fill="none">
                        <mask id="mask0_4313_2708" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="19" height="29">
                          <rect y="0.5" width="19" height="28" fill="#D9D9D9"/>
                        </mask>
                        <g mask="url(#mask0_4313_2708)">
                          <path d="M9.0026 19.2499L1.08594 11.3333H16.9193L9.0026 19.2499Z" fill="#1C1C1C"/>
                        </g>
                      </svg></a>
                    <a href="#" class="menu-itens-a"><svg xmlns="http://www.w3.org/2000/svg" width="28" height="29" viewBox="0 0 28 29" fill="none">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M14.0089 4.84032C16.4015 4.84144 18.6499 5.77426 20.3401 7.46338C22.0304 9.15475 22.9589 11.4021 22.9567 13.7924C22.9544 18.7254 18.9419 22.738 14.0067 22.738C12.5136 22.7369 11.0346 22.362 9.73193 21.6507L8.97717 21.2394L8.14365 21.4363L5.93843 21.957L6.47661 19.9574L6.71944 19.0605L6.25565 18.2554C5.47381 16.9023 5.06004 15.3552 5.06116 13.7837C5.0634 8.85297 9.07706 4.84032 14.0089 4.84032ZM9.30532 8.97072C9.56183 8.69069 9.86427 8.62068 10.0513 8.62068H10.0639C10.2456 8.62068 10.4264 8.62068 10.5851 8.62725C10.7845 8.63509 11.0057 8.64589 11.2152 9.11073C11.4639 9.66407 12.0077 11.0447 12.0772 11.1847C12.1466 11.3247 12.1942 11.4888 12.1012 11.6747C12.0083 11.8607 11.9601 11.9772 11.8212 12.1407C11.6812 12.3043 11.5288 12.5053 11.4033 12.6308C11.2633 12.7697 11.1162 12.9228 11.2786 13.2018C11.4422 13.4818 12.003 14.3953 12.8341 15.1357C13.9027 16.0878 14.803 16.3838 15.0831 16.5249C15.3631 16.6649 15.5255 16.6398 15.6891 16.4527C15.8526 16.2668 16.387 15.6389 16.5729 15.3588C16.7588 15.0788 16.9465 15.1259 17.203 15.2188C17.4595 15.3118 18.8339 15.9867 19.1128 16.1267C19.3929 16.2667 19.5794 16.3362 19.6488 16.4527C19.7183 16.5681 19.7177 17.1298 19.4848 17.7828C19.2518 18.4359 18.1098 19.0648 17.5968 19.1108C17.0837 19.1578 16.6042 19.3415 14.243 18.4107C11.4013 17.2906 9.60611 14.3787 9.46721 14.1928L9.46449 14.1892C9.31473 13.9891 8.32523 12.6675 8.32523 11.3006C8.32523 9.92514 9.04882 9.24963 9.30532 8.97072Z" fill="#25D366"/>
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M2.82094 13.7837C2.82318 7.61637 7.84377 2.6001 14.0111 2.6001C17.004 2.60122 19.8115 3.76583 21.9241 5.87948C24.0366 7.99425 25.1991 10.8051 25.1969 13.7946C25.1935 19.9608 20.1751 24.9782 14.0089 24.9782H14.0045C12.1317 24.9771 10.292 24.5091 8.65776 23.6175L2.79688 25.0023L4.31515 19.3755C3.33617 17.6796 2.81982 15.7551 2.82094 13.7837ZM20.3401 7.46338C18.6499 5.77426 16.4015 4.84144 14.0089 4.84032C9.07706 4.84032 5.0634 8.85297 5.06116 13.7837C5.06004 15.3552 5.47381 16.9023 6.25565 18.2554L6.71944 19.0605L6.47661 19.9574L5.93843 21.957L8.14365 21.4363L8.97717 21.2394L9.73193 21.6507C11.0346 22.362 12.5136 22.7369 14.0067 22.738C18.9419 22.738 22.9544 18.7254 22.9567 13.7924C22.9589 11.4021 22.0304 9.15475 20.3401 7.46338Z" fill="#25D366"/>
                      </svg>JÉSSICA</a>
                    <a href="#" class="menu-itens-a"><svg xmlns="http://www.w3.org/2000/svg" width="28" height="29" viewBox="0 0 28 29" fill="none">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M14.0089 4.84032C16.4015 4.84144 18.6499 5.77426 20.3401 7.46338C22.0304 9.15475 22.9589 11.4021 22.9567 13.7924C22.9544 18.7254 18.9419 22.738 14.0067 22.738C12.5136 22.7369 11.0346 22.362 9.73193 21.6507L8.97717 21.2394L8.14365 21.4363L5.93843 21.957L6.47661 19.9574L6.71944 19.0605L6.25565 18.2554C5.47381 16.9023 5.06004 15.3552 5.06116 13.7837C5.0634 8.85297 9.07706 4.84032 14.0089 4.84032ZM9.30532 8.97072C9.56183 8.69069 9.86427 8.62068 10.0513 8.62068H10.0639C10.2456 8.62068 10.4264 8.62068 10.5851 8.62725C10.7845 8.63509 11.0057 8.64589 11.2152 9.11073C11.4639 9.66407 12.0077 11.0447 12.0772 11.1847C12.1466 11.3247 12.1942 11.4888 12.1012 11.6747C12.0083 11.8607 11.9601 11.9772 11.8212 12.1407C11.6812 12.3043 11.5288 12.5053 11.4033 12.6308C11.2633 12.7697 11.1162 12.9228 11.2786 13.2018C11.4422 13.4818 12.003 14.3953 12.8341 15.1357C13.9027 16.0878 14.803 16.3838 15.0831 16.5249C15.3631 16.6649 15.5255 16.6398 15.6891 16.4527C15.8526 16.2668 16.387 15.6389 16.5729 15.3588C16.7588 15.0788 16.9465 15.1259 17.203 15.2188C17.4595 15.3118 18.8339 15.9867 19.1128 16.1267C19.3929 16.2667 19.5794 16.3362 19.6488 16.4527C19.7183 16.5681 19.7177 17.1298 19.4848 17.7828C19.2518 18.4359 18.1098 19.0648 17.5968 19.1108C17.0837 19.1578 16.6042 19.3415 14.243 18.4107C11.4013 17.2906 9.60611 14.3787 9.46721 14.1928L9.46449 14.1892C9.31473 13.9891 8.32523 12.6675 8.32523 11.3006C8.32523 9.92514 9.04882 9.24963 9.30532 8.97072Z" fill="#25D366"/>
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M2.82094 13.7837C2.82318 7.61637 7.84377 2.6001 14.0111 2.6001C17.004 2.60122 19.8115 3.76583 21.9241 5.87948C24.0366 7.99425 25.1991 10.8051 25.1969 13.7946C25.1935 19.9608 20.1751 24.9782 14.0089 24.9782H14.0045C12.1317 24.9771 10.292 24.5091 8.65776 23.6175L2.79688 25.0023L4.31515 19.3755C3.33617 17.6796 2.81982 15.7551 2.82094 13.7837ZM20.3401 7.46338C18.6499 5.77426 16.4015 4.84144 14.0089 4.84032C9.07706 4.84032 5.0634 8.85297 5.06116 13.7837C5.06004 15.3552 5.47381 16.9023 6.25565 18.2554L6.71944 19.0605L6.47661 19.9574L5.93843 21.957L8.14365 21.4363L8.97717 21.2394L9.73193 21.6507C11.0346 22.362 12.5136 22.7369 14.0067 22.738C18.9419 22.738 22.9544 18.7254 22.9567 13.7924C22.9589 11.4021 22.0304 9.15475 20.3401 7.46338Z" fill="#25D366"/>
                      </svg>ROBERTO</a>
                    <a href="#" class="menu-itens-a"><svg xmlns="http://www.w3.org/2000/svg" width="28" height="29" viewBox="0 0 28 29" fill="none">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M14.0089 4.84032C16.4015 4.84144 18.6499 5.77426 20.3401 7.46338C22.0304 9.15475 22.9589 11.4021 22.9567 13.7924C22.9544 18.7254 18.9419 22.738 14.0067 22.738C12.5136 22.7369 11.0346 22.362 9.73193 21.6507L8.97717 21.2394L8.14365 21.4363L5.93843 21.957L6.47661 19.9574L6.71944 19.0605L6.25565 18.2554C5.47381 16.9023 5.06004 15.3552 5.06116 13.7837C5.0634 8.85297 9.07706 4.84032 14.0089 4.84032ZM9.30532 8.97072C9.56183 8.69069 9.86427 8.62068 10.0513 8.62068H10.0639C10.2456 8.62068 10.4264 8.62068 10.5851 8.62725C10.7845 8.63509 11.0057 8.64589 11.2152 9.11073C11.4639 9.66407 12.0077 11.0447 12.0772 11.1847C12.1466 11.3247 12.1942 11.4888 12.1012 11.6747C12.0083 11.8607 11.9601 11.9772 11.8212 12.1407C11.6812 12.3043 11.5288 12.5053 11.4033 12.6308C11.2633 12.7697 11.1162 12.9228 11.2786 13.2018C11.4422 13.4818 12.003 14.3953 12.8341 15.1357C13.9027 16.0878 14.803 16.3838 15.0831 16.5249C15.3631 16.6649 15.5255 16.6398 15.6891 16.4527C15.8526 16.2668 16.387 15.6389 16.5729 15.3588C16.7588 15.0788 16.9465 15.1259 17.203 15.2188C17.4595 15.3118 18.8339 15.9867 19.1128 16.1267C19.3929 16.2667 19.5794 16.3362 19.6488 16.4527C19.7183 16.5681 19.7177 17.1298 19.4848 17.7828C19.2518 18.4359 18.1098 19.0648 17.5968 19.1108C17.0837 19.1578 16.6042 19.3415 14.243 18.4107C11.4013 17.2906 9.60611 14.3787 9.46721 14.1928L9.46449 14.1892C9.31473 13.9891 8.32523 12.6675 8.32523 11.3006C8.32523 9.92514 9.04882 9.24963 9.30532 8.97072Z" fill="#25D366"/>
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M2.82094 13.7837C2.82318 7.61637 7.84377 2.6001 14.0111 2.6001C17.004 2.60122 19.8115 3.76583 21.9241 5.87948C24.0366 7.99425 25.1991 10.8051 25.1969 13.7946C25.1935 19.9608 20.1751 24.9782 14.0089 24.9782H14.0045C12.1317 24.9771 10.292 24.5091 8.65776 23.6175L2.79688 25.0023L4.31515 19.3755C3.33617 17.6796 2.81982 15.7551 2.82094 13.7837ZM20.3401 7.46338C18.6499 5.77426 16.4015 4.84144 14.0089 4.84032C9.07706 4.84032 5.0634 8.85297 5.06116 13.7837C5.06004 15.3552 5.47381 16.9023 6.25565 18.2554L6.71944 19.0605L6.47661 19.9574L5.93843 21.957L8.14365 21.4363L8.97717 21.2394L9.73193 21.6507C11.0346 22.362 12.5136 22.7369 14.0067 22.738C18.9419 22.738 22.9544 18.7254 22.9567 13.7924C22.9589 11.4021 22.0304 9.15475 20.3401 7.46338Z" fill="#25D366"/>
                      </svg>GILCÉIA</a>
                    
                </div>
            </div>

        </div>
        <div class="menu-itens col-lg-8 col-sm-8 col-12">
            <div class="cgo-img"><a href="#"><img src=/Logo CGO.jpg" alt="CGO"></a>
            </div>
            <a href="#" class="menu-itens-a">INÍCIO</a>
            <a href="#" class="menu-itens-a">CURSOS</a>
            <a href="#" class="menu-itens-a">COMO FUNCIONA</a>
            <a href="#" class="menu-itens-a">CERTIFICADO</a>
            <div class="dropdown">
                <a class="btn btn-secondary dropdown-toggle btn-menu-itens" href="#" role="button"
                    id="dropdownMenuLink" data-bs-toggle="dropdown" aria-expanded="false">
                    <svg class="svg-what" xmlns="http://www.w3.org/2000/svg" width="29" height="28"
                        viewBox="0 0 29 28" fill="none">
                        <path fill-rule="evenodd" clip-rule="evenodd"
                            d="M14.3917 4.34032C16.7843 4.34144 19.0327 5.27426 20.723 6.96338C22.4132 8.65475 23.3417 10.9021 23.3395 13.2924C23.3372 18.2254 19.3247 22.238 14.3895 22.238C12.8964 22.2369 11.4174 21.862 10.1147 21.1507L9.35998 20.7394L8.52646 20.9363L6.32124 21.457L6.85942 19.4574L7.10226 18.5605L6.63846 17.7554C5.85663 16.4023 5.44285 14.8552 5.44397 13.2837C5.44621 8.35297 9.45988 4.34032 14.3917 4.34032ZM9.68814 8.47072C9.94464 8.19069 10.2471 8.12068 10.4341 8.12068H10.4467C10.6284 8.12068 10.8092 8.12068 10.9679 8.12725C11.1673 8.13509 11.3885 8.14589 11.598 8.61073C11.8467 9.16407 12.3905 10.5447 12.46 10.6847C12.5294 10.8247 12.577 10.9888 12.484 11.1747C12.3911 11.3607 12.3429 11.4772 12.204 11.6407C12.064 11.8043 11.9116 12.0053 11.7862 12.1308C11.6461 12.2697 11.499 12.4228 11.6615 12.7018C11.825 12.9818 12.3858 13.8953 13.2169 14.6357C14.2855 15.5878 15.1859 15.8838 15.4659 16.0249C15.7459 16.1649 15.9083 16.1398 16.0719 15.9527C16.2354 15.7668 16.7698 15.1389 16.9557 14.8588C17.1417 14.5788 17.3293 14.6259 17.5858 14.7188C17.8423 14.8118 19.2167 15.4867 19.4957 15.6267C19.7757 15.7667 19.9622 15.8362 20.0316 15.9527C20.1011 16.0681 20.1005 16.6298 19.8676 17.2828C19.6346 17.9359 18.4926 18.5648 17.9796 18.6108C17.4666 18.6578 16.987 18.8415 14.6258 17.9107C11.7841 16.7906 9.98892 13.8787 9.85003 13.6928L9.8473 13.6892C9.69755 13.4891 8.70804 12.1675 8.70804 10.8006C8.70804 9.42514 9.43163 8.74963 9.68814 8.47072Z"
                            fill="#25D366" />
                        <path fill-rule="evenodd" clip-rule="evenodd"
                            d="M3.20375 13.2837C3.20599 7.11637 8.22658 2.1001 14.3939 2.1001C17.3868 2.10122 20.1943 3.26583 22.3069 5.37948C24.4194 7.49425 25.5819 10.3051 25.5797 13.2946C25.5763 19.4608 20.5579 24.4782 14.3917 24.4782H14.3873C12.5145 24.4771 10.6748 24.0091 9.04057 23.1175L3.17969 24.5023L4.69796 18.8755C3.71899 17.1796 3.20263 15.2551 3.20375 13.2837ZM20.723 6.96338C19.0327 5.27426 16.7843 4.34144 14.3917 4.34032C9.45988 4.34032 5.44621 8.35297 5.44397 13.2837C5.44285 14.8552 5.85663 16.4023 6.63846 17.7554L7.10226 18.5605L6.85942 19.4574L6.32124 21.457L8.52646 20.9363L9.35998 20.7394L10.1147 21.1507C11.4174 21.862 12.8964 22.2369 14.3895 22.238C19.3247 22.238 23.3372 18.2254 23.3395 13.2924C23.3417 10.9021 22.4132 8.65475 20.723 6.96338Z"
                            fill="#25D366" />
                    </svg>ATENDIMENTO
                </a>
                <ul class="dropdown-menu" style="padding: 10px;" aria-labelledby="dropdownMenuLink">
                    <li><a class="dropdown-item" href="#">FALE CONOSCO</a></li>
                    <li><a class="dropdown-item" href="#">DÚVIDAS</a></li>
                    <li><a class="dropdown-item" href="#">MATRÍCULA</a></li>
                </ul>
            </div>
            <div>
                <a href="#" class="btn btn-dark btn-aluno" role="button"><svg xmlns="http://www.w3.org/2000/svg"
                        class="svg-what" width="24" height="24" viewBox="0 0 24 24" fill="none">
                        <mask id="mask0_4201_1497" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0"
                            width="24" height="24">
                            <rect x="0.265625" y="0.382812" width="23.2344" height="23.2344" fill="#D9D9D9" />
                        </mask>
                        <g mask="url(#mask0_4201_1497)">
                            <path
                                d="M11.8848 22.165C10.723 21.0678 9.39191 20.2288 7.89136 19.6479C6.3908 19.067 4.81764 18.7766 3.17188 18.7766V8.12752C4.80151 8.12752 6.3666 8.42199 7.86715 9.01091C9.36771 9.59984 10.7069 10.451 11.8848 11.5643C13.0626 10.451 14.4018 9.59984 15.9024 9.01091C17.4029 8.42199 18.968 8.12752 20.5977 8.12752V18.7766C18.9358 18.7766 17.3586 19.067 15.8661 19.6479C14.3736 20.2288 13.0465 21.0678 11.8848 22.165ZM11.8848 9.09562C10.8199 9.09562 9.90823 8.71645 9.14989 7.95811C8.39154 7.19976 8.01237 6.28813 8.01237 5.22323C8.01237 4.15832 8.39154 3.24669 9.14989 2.48835C9.90823 1.73 10.8199 1.35083 11.8848 1.35083C12.9497 1.35083 13.8613 1.73 14.6196 2.48835C15.378 3.24669 15.7572 4.15832 15.7572 5.22323C15.7572 6.28813 15.378 7.19976 14.6196 7.95811C13.8613 8.71645 12.9497 9.09562 11.8848 9.09562Z"
                                fill="white" />
                        </g>
                    </svg>SOU ALUNO</a>
            </div>
        </div>
    </div>
    <div class="main-banner-mobile">
        <img class="main-banner-mobile-px" src="/Banner Portal Mundo CGO Mobile.png" alt="">
    </div>
    <div class="main-banner">
        <img class="main-banner-px" src="/Banner Portal Mundo CGO.png" alt="">
    </div>
    <div class="" style="padding: 0 10px;">
        <div class="container-categoria">
            <div class="container-artigo col-lg-8 col-sm-8 col-12">
                <h2 class="h2-title">
                    PESQUISE SEU CONTEÚDO
                </h2>

                <div class="container-pesquisa col-lg-12 col-sm-12">
                    <div class="btn-group col-lg-12 col-sm-12">
                        <button type="button" class="btn btn-danger dropdown-toggle btn-color-amarelo "
                            data-bs-toggle="dropdown" aria-expanded="false">
                            BUSCA POR CATEGORIAS
                        </button>

                        <ul class="dropdown-menu col-lg-12 col-sm-12 col-12 padding-0">
                            <li class="padding-0"><button class="dropdown-item" type="button"><table style="margin: 0;" class="  table table-bordered">
                                <tbody>
                                  <tr class="tr-alain-center">
                                    <td>ADMINISTRAÇÃO</td>
                                    <td>DIREITO</td>
                                    <td>JORNALISMO</td>
                                    <td>PSICOLOGIA</td>
                                  </tr>
                                  <tr class="tr-alain-center">
                                    <td>AGRICULTURA</td>
                                    <td>EDUCAÇÃO</td>
                                    <td>LOGÍSTICA</td>
                                    <td>RECURSOS HUMANOS</td>
                                  </tr>
                                  <tr class="tr-alain-center">
                                    <td>ARTES</td>
                                    <td>ESPORTE</td>
                                    <td>MARKETING</td>
                                    <td>RELIGIÃO</td>
                                  </tr>
                                  <tr class="tr-alain-center">
                                    <td>ASSISTÊNCIA SOCIAL</td>
                                    <td>ESTÉTICA</td>
                                    <td>MECÂNICA</td>
                                    <td>SAÚDE</td>
                                  </tr>
                                  <tr class="tr-alain-center">
                                    <td>CIÊNCIA E TECNOLOGIA</td>
                                    <td>GESTÃO E QUALIDADE</td>
                                    <td>MEIO AMBIENTE</td>
                                    <td>MEIO AMBIENTE</td>
                                  </tr>
                                  <tr class="tr-alain-center">
                                    <td>CONSTRUÇÃO CIVIL</td>
                                    <td>IDIOMAS</td>
                                    <td>MÚSICA</td>
                                    <td>SEGURANÇA</td>
                                  </tr>
                                  <tr class="tr-alain-center">
                                    <td>CONTABILIDADE</td>
                                    <td>INDÚSTRIA E TECNOLOGIA</td>
                                    <td>NUTRIÇÃO</td>
                                    <td>TÉCNICAS PROFISSIONAIS</td>
                                  </tr>
                                  <tr class="tr-alain-center">
                                    <td>CULINÁRIA</td>
                                    <td>INFORMÁTICA</td>
                                    <td>OUTRAS ÁREAS</td>
                                    <td>TURISMO</td>
                                  </tr>
                                </tbody>
                              </table></button></li>
                        </ul>
                        <div class="barra">
                            <input type="text" class="search-bar" placeholder="  BUSCAR POR CONTÉUDO">
                            <button class="busca">
                                <svg xmlns="http://www.w3.org/2000/svg" class="lupa" width="25" height="24"
                                    viewBox="0 0 25 24" fill="none">
                                    <mask id="mask0_4230_1516" style="mask-type:alpha" maskUnits="userSpaceOnUse"
                                        x="0" y="0" width="25" height="24">
                                        <rect x="0.5" width="24" height="24" fill="#D9D9D9" />
                                    </mask>
                                    <g mask="url(#mask0_4230_1516)">
                                        <path
                                            d="M20.1 21L13.8 14.7C13.3 15.1 12.725 15.4167 12.075 15.65C11.425 15.8833 10.7333 16 10 16C8.18333 16 6.64583 15.3708 5.3875 14.1125C4.12917 12.8542 3.5 11.3167 3.5 9.5C3.5 7.68333 4.12917 6.14583 5.3875 4.8875C6.64583 3.62917 8.18333 3 10 3C11.8167 3 13.3542 3.62917 14.6125 4.8875C15.8708 6.14583 16.5 7.68333 16.5 9.5C16.5 10.2333 16.3833 10.925 16.15 11.575C15.9167 12.225 15.6 12.8 15.2 13.3L21.5 19.6L20.1 21ZM10 14C11.25 14 12.3125 13.5625 13.1875 12.6875C14.0625 11.8125 14.5 10.75 14.5 9.5C14.5 8.25 14.0625 7.1875 13.1875 6.3125C12.3125 5.4375 11.25 5 10 5C8.75 5 7.6875 5.4375 6.8125 6.3125C5.9375 7.1875 5.5 8.25 5.5 9.5C5.5 10.75 5.9375 11.8125 6.8125 12.6875C7.6875 13.5625 8.75 14 10 14Z"
                                            fill="white" />
                                    </g>
                                </svg>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="container-pesquisa-mobile col-12">
                    <div class="btn-group col-12 container-btn-todos-center">
                        <button type="button" class="btn btn-danger dropdown-toggle btn-color-amarelo "
                            data-bs-toggle="dropdown" aria-expanded="false">
                            BUSCA POR CATEGORIAS
                        </button>
                        <ul class="dropdown-menu col-lg-12 col-sm-12 col-12 padding-0">
                            <li class="padding-0"><button class="dropdown-item" type="button"><table style="margin: 0;" class="  table table-bordered">
                                <tbody>
                                    <tr class="tr-alain-center"><td>ADMINISTRAÇÃO</td></tr>
                                    <tr class="tr-alain-center"><td>DIREITO</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>JORNALISMO</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>PSICOLOGIA</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>AGRICULTURA</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>EDUCAÇÃO</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>LOGÍSTICA</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>RECURSOS HUMANOS</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>ARTES</td></tr>                                 
                                    
                                    <tr class="tr-alain-center"><td>ESPORTE</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>MARKETING</td></tr>
                                    
                                    <tr class="tr-alain-center"> <td>RELIGIÃO</td></tr>
                                   
                                    <tr class="tr-alain-center"><td>ASSISTÊNCIA SOCIAL</td></tr>                          
                                    
                                    <tr class="tr-alain-center"><td>ESTÉTICA</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>MECÂNICA</td></tr>
                                    
                                    <tr class="tr-alain-center"> <td>SAÚDE</td></tr>
                                
                                    <tr class="tr-alain-center"><td>CIÊNCIA E TECNOLOGIA</td></tr>                      
                                    
                                    <tr class="tr-alain-center"><td>GESTÃO E QUALIDADE</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>MEIO AMBIENTE</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>MEIO AMBIENTE</td> </tr>
                                         
                                    <tr class="tr-alain-center"><td>CONSTRUÇÃO CIVIL</td></tr>                               
                                    
                                    <tr class="tr-alain-center"><td>IDIOMAS</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>MÚSICA</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>SEGURANÇA</td></tr>
                                             
                                    <tr class="tr-alain-center"><td>CONTABILIDADE</td></tr>                       
                                    
                                    <tr class="tr-alain-center"><td>INDÚSTRIA E TECNOLOGIA</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>NUTRIÇÃO</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>TÉCNICAS PROFISSIONAIS</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>CULINÁRIA</td></tr>                                   
                                    
                                    <tr class="tr-alain-center"><td>INFORMÁTICA</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>OUTRAS ÁREAS</td></tr>
                                    
                                    <tr class="tr-alain-center"><td>TURISMO</td></tr>
                                </tbody>
                              </table></button></li>
                        </ul>
                    </div>
                    <div class="barra">
                        <input type="text" class="search-bar" placeholder="  BUSCAR POR CONTÉUDO">
                        <button class="busca">
                            <svg xmlns="http://www.w3.org/2000/svg" class="lupa" width="25" height="24"
                                viewBox="0 0 25 24" fill="none">
                                <mask id="mask0_4230_1516" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0"
                                    y="0" width="25" height="24">
                                    <rect x="0.5" width="24" height="24" fill="#D9D9D9" />
                                </mask>
                                <g mask="url(#mask0_4230_1516)">
                                    <path
                                        d="M20.1 21L13.8 14.7C13.3 15.1 12.725 15.4167 12.075 15.65C11.425 15.8833 10.7333 16 10 16C8.18333 16 6.64583 15.3708 5.3875 14.1125C4.12917 12.8542 3.5 11.3167 3.5 9.5C3.5 7.68333 4.12917 6.14583 5.3875 4.8875C6.64583 3.62917 8.18333 3 10 3C11.8167 3 13.3542 3.62917 14.6125 4.8875C15.8708 6.14583 16.5 7.68333 16.5 9.5C16.5 10.2333 16.3833 10.925 16.15 11.575C15.9167 12.225 15.6 12.8 15.2 13.3L21.5 19.6L20.1 21ZM10 14C11.25 14 12.3125 13.5625 13.1875 12.6875C14.0625 11.8125 14.5 10.75 14.5 9.5C14.5 8.25 14.0625 7.1875 13.1875 6.3125C12.3125 5.4375 11.25 5 10 5C8.75 5 7.6875 5.4375 6.8125 6.3125C5.9375 7.1875 5.5 8.25 5.5 9.5C5.5 10.75 5.9375 11.8125 6.8125 12.6875C7.6875 13.5625 8.75 14 10 14Z"
                                        fill="white" />
                                </g>
                            </svg>
                        </button>
                    </div>
                </div>
                <div class="linha-bege"></div>
                <h2 class="h2-title">
                    ARTIGOS POR CATEGORIA
                </h2>
            </div>
        </div>
        <div class="container-center">
            <div class="container-curso col-lg-8 col-sm-8 col-12">
                <h3 class="container-curso-h3">
                    ADMINISTRAÇÃO <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 25 25"
                        fill="none">
                        <mask id="mask0_4233_4408" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0"
                            width="25" height="25">
                            <rect x="0.25" y="0.755615" width="24" height="24" fill="#D9D9D9" />
                        </mask>
                        <g mask="url(#mask0_4233_4408)">
                            <path
                                d="M8.275 22.7556L6.5 20.9806L14.725 12.7556L6.5 4.53062L8.275 2.75562L18.275 12.7556L8.275 22.7556Z"
                                fill="white" />
                        </g>
                    </svg>
                </h3>
            </div>
        </div>
        <div class="container-center">
            <div class="container-btn-card col-lg-8 col-sm-8">
                <button class="btn-movimentar-card"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 73 73" height="73" width="73"><g xmlns="http://www.w3.org/2000/svg" transform="matrix(-1 0 0 1 73 -0)"><g id="Group 1000005805" filter="url(#filter0_d_4220_2447)"><circle id="Ellipse 325" cx="36.5" cy="31.5" r="23.5" fill="white" /><g id="arrow_downward_alt"><mask id="mask0_4220_2447" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="20" y="15" width="33" height="33"><rect id="Bounding box" x="20" y="48" width="33" height="33" transform="rotate(-90 20 48)" fill="#D9D9D9" /></mask><g mask="url(#mask0_4220_2447)"><path id="arrow_downward_alt_2" d="M44.75 31.5L36.5 39.75L34.575 37.825L39.525 32.875L26.875 32.875L26.875 30.125L39.525 30.125L34.575 25.175L36.5 23.25L44.75 31.5Z" fill="#1C1B1F" /></g></g></g><defs><filter id="filter0_d_4220_2447" x="0.2" y="0.2" width="72.6" height="72.6" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB"><feFlood flood-opacity="0" result="BackgroundImageFix" /><feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha" /><feOffset dy="5" /><feGaussianBlur stdDeviation="6.4" /><feComposite in2="hardAlpha" operator="out" /><feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.4 0" /><feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_4220_2447" /><feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_4220_2447" result="shape" /></filter></defs></g></svg>
                </button>
                <button class="btn-movimentar-card"><svg xmlns="http://www.w3.org/2000/svg" width="73" height="73" viewBox="0 0 73 73" fill="none">
                    <g filter="url(#filter0_d_4220_2447)">
                      <circle cx="36.5" cy="31.5" r="23.5" fill="white"/>
                      <mask id="mask0_4220_2447" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="20" y="15" width="33" height="33">
                        <rect x="20" y="48" width="33" height="33" transform="rotate(-90 20 48)" fill="#D9D9D9"/>
                      </mask>
                      <g mask="url(#mask0_4220_2447)">
                        <path d="M44.75 31.5L36.5 39.75L34.575 37.825L39.525 32.875L26.875 32.875L26.875 30.125L39.525 30.125L34.575 25.175L36.5 23.25L44.75 31.5Z" fill="#1C1B1F"/>
                      </g>
                    </g>
                    <defs>
                      <filter id="filter0_d_4220_2447" x="0.2" y="0.2" width="72.6" height="72.6" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
                        <feFlood flood-opacity="0" result="BackgroundImageFix"/>
                        <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
                        <feOffset dy="5"/>
                        <feGaussianBlur stdDeviation="6.4"/>
                        <feComposite in2="hardAlpha" operator="out"/>
                        <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.4 0"/>
                        <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_4220_2447"/>
                        <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_4220_2447" result="shape"/>
                      </filter>
                    </defs>
                  </svg>
                </button>
            </div>
            <div class=" container-grid col-lg-8 col-sm-8 col-12">
                <div class="card card-edit">

                    <div class="card-body">
                        <div class="box-card">
                            <span class="text-box-card">
                                TÉCNICAS PROFISSIONAIS
                            </span>
                            <span class="date-box-card">
                                26/09/2024
                            </span>
                        </div>
                        <p class="card-text">iOS: o que é internacionalização e sua configuração inicial em um
                            projeto...</p>
                        <a href="#" class="btn btn-primary btn-card">LER MAIS
                        </a>
                    </div>
                </div>
                <div class="card card-edit">
                    <div class="card-body">
                        <div class="box-card">
                            <span class="text-box-card">
                                TÉCNICAS PROFISSIONAIS
                            </span>
                            <span class="date-box-card">
                                26/09/2024
                            </span>
                        </div>
                        <p class="card-text">iOS: o que é internacionalização e sua configuração inicial em um
                            projeto...</p>
                        <a href="#" class="btn btn-primary btn-card">LER MAIS
                        </a>
                    </div>
                </div>
                <div class="card card-edit">
                    <div class="card-body">
                        <div class="box-card">
                            <span class="text-box-card">
                                TÉCNICAS PROFISSIONAIS
                            </span>
                            <span class="date-box-card">
                                26/09/2024
                            </span>
                        </div>
                        <p class="card-text">iOS: o que é internacionalização e sua configuração inicial em um
                            projeto...</p>
                        <a href="#" class="btn btn-primary btn-card">LER MAIS
                        </a>
                    </div>
                </div>
                <div class="card card-edit">
                    <div class="card-body">
                        <div class="box-card">
                            <span class="text-box-card">
                                TÉCNICAS PROFISSIONAIS
                            </span>
                            <span class="date-box-card">
                                26/09/2024
                            </span>
                        </div>
                        <p class="card-text">iOS: o que é internacionalização e sua configuração inicial em um
                            projeto...</p>
                        <a href="#" class="btn btn-primary btn-card">LER MAIS
                        </a>
                    </div>
                </div>
            </div>

        </div>
        <div class="container-center-mobile">
            <a href="#" class="btn btn-primary btn-card-amarelo btn-card-mobile" tabindex="-1" role="button">VER TODOS(72)</a>
        </div>
        <div class="container-center">
            <a href="#" class="btn btn-primary btn-card-amarelo " tabindex="-1" role="button">VER TODOS DE
                ADMINISTRAÇÃO</a>
        </div>
        <div class="container-ver-todos">

        </div>
        <div class="container-center">
            <div class="container-curso col-lg-8 col-sm-8 col-12">
                <h3 class="container-curso-h3">
                    ADMINISTRAÇÃO <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 25 25"
                        fill="none">
                        <mask id="mask0_4233_4408" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0"
                            width="25" height="25">
                            <rect x="0.25" y="0.755615" width="24" height="24" fill="#D9D9D9" />
                        </mask>
                        <g mask="url(#mask0_4233_4408)">
                            <path
                                d="M8.275 22.7556L6.5 20.9806L14.725 12.7556L6.5 4.53062L8.275 2.75562L18.275 12.7556L8.275 22.7556Z"
                                fill="white" />
                        </g>
                    </svg>
                </h3>
            </div>
        </div>
        <div class="container-center">
            <div class=" container-grid col-lg-8 col-sm-8 col-12">
                <div class="card card-edit">
                    <div class="card-body">
                        <div class="box-card">
                            <span class="text-box-card">
                                TÉCNICAS PROFISSIONAIS
                            </span>
                            <span class="date-box-card">
                                26/09/2024
                            </span>
                        </div>
                        <p class="card-text">iOS: o que é internacionalização e sua configuração inicial em um
                            projeto...</p>
                        <a href="#" class="btn btn-primary btn-card">LER MAIS
                        </a>
                    </div>
                </div>
                <div class="card card-edit">
                    <div class="card-body">
                        <div class="box-card">
                            <span class="text-box-card">
                                TÉCNICAS PROFISSIONAIS
                            </span>
                            <span class="date-box-card">
                                26/09/2024
                            </span>
                        </div>
                        <p class="card-text">iOS: o que é internacionalização e sua configuração inicial em um
                            projeto...</p>
                        <a href="#" class="btn btn-primary btn-card">LER MAIS
                        </a>
                    </div>
                </div>
                <div class="card card-edit">
                    <div class="card-body">
                        <div class="box-card">
                            <span class="text-box-card">
                                TÉCNICAS PROFISSIONAIS
                            </span>
                            <span class="date-box-card">
                                26/09/2024
                            </span>
                        </div>
                        <p class="card-text">iOS: o que é internacionalização e sua configuração inicial em um
                            projeto...</p>
                        <a href="#" class="btn btn-primary btn-card">LER MAIS
                        </a>
                    </div>
                </div>
                <div class="card card-edit">
                    <div class="card-body">
                        <div class="box-card">
                            <span class="text-box-card">
                                TÉCNICAS PROFISSIONAIS
                            </span>
                            <span class="date-box-card">
                                26/09/2024
                            </span>
                        </div>
                        <p class="card-text">iOS: o que é internacionalização e sua configuração inicial em um
                            projeto...</p>
                        <a href="#" class="btn btn-primary btn-card">LER MAIS
                        </a>
                    </div>
                </div>
            </div>
            <div class="container-btn-card col-lg-8 col-sm-8">
                <button class="btn-movimentar-card"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 73 73" height="73" width="73"><g xmlns="http://www.w3.org/2000/svg" transform="matrix(-1 0 0 1 73 -0)"><g id="Group 1000005805" filter="url(#filter0_d_4220_2447)"><circle id="Ellipse 325" cx="36.5" cy="31.5" r="23.5" fill="white" /><g id="arrow_downward_alt"><mask id="mask0_4220_2447" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="20" y="15" width="33" height="33"><rect id="Bounding box" x="20" y="48" width="33" height="33" transform="rotate(-90 20 48)" fill="#D9D9D9" /></mask><g mask="url(#mask0_4220_2447)"><path id="arrow_downward_alt_2" d="M44.75 31.5L36.5 39.75L34.575 37.825L39.525 32.875L26.875 32.875L26.875 30.125L39.525 30.125L34.575 25.175L36.5 23.25L44.75 31.5Z" fill="#1C1B1F" /></g></g></g><defs><filter id="filter0_d_4220_2447" x="0.2" y="0.2" width="72.6" height="72.6" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB"><feFlood flood-opacity="0" result="BackgroundImageFix" /><feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha" /><feOffset dy="5" /><feGaussianBlur stdDeviation="6.4" /><feComposite in2="hardAlpha" operator="out" /><feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.4 0" /><feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_4220_2447" /><feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_4220_2447" result="shape" /></filter></defs></g></svg>
                </button>
                <button class="btn-movimentar-card"><svg xmlns="http://www.w3.org/2000/svg" width="73" height="73" viewBox="0 0 73 73" fill="none">
                    <g filter="url(#filter0_d_4220_2447)">
                      <circle cx="36.5" cy="31.5" r="23.5" fill="white"/>
                      <mask id="mask0_4220_2447" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="20" y="15" width="33" height="33">
                        <rect x="20" y="48" width="33" height="33" transform="rotate(-90 20 48)" fill="#D9D9D9"/>
                      </mask>
                      <g mask="url(#mask0_4220_2447)">
                        <path d="M44.75 31.5L36.5 39.75L34.575 37.825L39.525 32.875L26.875 32.875L26.875 30.125L39.525 30.125L34.575 25.175L36.5 23.25L44.75 31.5Z" fill="#1C1B1F"/>
                      </g>
                    </g>
                    <defs>
                      <filter id="filter0_d_4220_2447" x="0.2" y="0.2" width="72.6" height="72.6" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
                        <feFlood flood-opacity="0" result="BackgroundImageFix"/>
                        <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
                        <feOffset dy="5"/>
                        <feGaussianBlur stdDeviation="6.4"/>
                        <feComposite in2="hardAlpha" operator="out"/>
                        <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.4 0"/>
                        <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_4220_2447"/>
                        <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_4220_2447" result="shape"/>
                      </filter>
                    </defs>
                  </svg>
                </button>
            </div>
        </div>
        <div class="container-center-mobile">
            <a href="#" class="btn btn-primary btn-card-amarelo btn-card-mobile" tabindex="-1" role="button">VER TODOS(72)</a>
        </div>
        <div class="container-center">
            <a href="#" class="btn btn-primary btn-card-amarelo " tabindex="-1" role="button">VER TODOS DE
                ADMINISTRAÇÃO</a>
        </div>
    </div>
    </main>
    <footer>
        <img style="width: 100%;"
            src="/FireShot Capture 004 - Curso Gratuito de Barbeiro - Cursos Grátis Online_ - www.cursosgratisonline.com.br 1.png Capture 004 - Curso Gratuito de Barbeiro - Cursos Grátis Online_ - www.cursosgratisonline.com.br 1.png"
            alt="">
    </footer>
