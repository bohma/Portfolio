<template>
  <div class="MainWrap">
    <div class="welcome">
      <div class="wrapper">
        <div class="nav">
          <img src="../assets/logo.png" alt="" class="nav__logo" />
          <div class="nav__links" :class="{ active: isActive }">
            <a href="#" class="nav__links-link">Главная</a>
            <a href="#" class="nav__links-link">Об авторе</a>
            <a href="#" class="nav__links-link">Работы</a>
            <a href="#" class="nav__links-link">Процесс</a>
            <a href="#" class="nav__links-link">Контакты</a>
          </div>
          <div
            class="nav__burger"
            :class="{ active: isActive }"
            @click="showBurger"
          >
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>

        <div class="welcome__content">
          <img src="../assets/Frame.png" class="welcome__image" />
          <div class="welcome__info">
            <div class="welcome__info-title">Web-Разработка</div>
            <div class="welcome__info-text description">
              Процедура создания WEB-приложения или WEB-сайта. Основными этапами
              этого процесса являются такие мероприятия, как WEB-дизайн, вёрстка
              страниц сайта, WEB-программирование на стороне сервера и клиента
            </div>
            <div class="welcome__info-button">
              <a href="#" class="btn">Написать мне</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="about">
      <div class="wrapper">
        <div class="about__content">
          <div class="about__skills">
            <div class="about__skills-title title">Мои навыки</div>
            <div class="about__skills-text">
              <div class="about__skills-text__skill">Javascript</div>
              <div class="about__skills-text__skill">Vue</div>
              <div class="about__skills-text__skill">SCSS</div>
            </div>
          </div>
          <img src="../assets/1.jpg" class="about__img" />
        </div>
      </div>
    </div>
    <div class="ability">
      <div class="wrapper">
        <div class="ability__content">
          <div class="ability__title title">Какого рода проект вы хотите?</div>
          <div class="ability__item">
            <div class="ability__item-img">
              <div class="ability__item-img__landing-page">
                <svg viewBox="0 0 141 104">
                  <use xlink:href="#landing-page"></use>
                </svg>
              </div>
            </div>
            <div class="ability__item-info">
              <div class="ability__item-info_title">Landing Page</div>
              <div class="ability__item-info_text description">
                Лендинг — это любая страница, которая призывает пользователя
                что-то сделать. Например, подписаться на рассылку, купить билет
                на конференцию или просто скачать презентацию.
              </div>
            </div>
          </div>
          <div class="ability__item">
            <div class="ability__item-img">
              <div class="ability__item-img__web-app">
                <svg viewBox="0 0 151 126">
                  <use xlink:href="#web-app"></use>
                </svg>
              </div>
            </div>
            <div class="ability__item-info">
              <div class="ability__item-info_title">
                Single Page Application
              </div>
              <div class="ability__item-info_text description">
                Single Page Application — это одностраничное веб-приложение.
                Благодаря динамическому обновлению во время использования не
                нужно перезагружать или подгружать дополнительные страницы в
                отличие от вебсайтов. Веб-приложения созданы для взаимодействия
                с пользователями. Веб приложения тоже могут быть
                информативными,<br />
                но они могут также и обрабатывать информацию, полученную от
                пользователей.
              </div>
            </div>
          </div>
          <div class="ability__item">
            <div class="ability__item-img">
              <div class="ability__item-img__desktop">
                <svg viewBox="0 0 150 130">
                  <use xlink:href="#desktop"></use>
                </svg>
              </div>

              <div class="ability__item-img__tablet">
                <svg viewBox="0 0 108 130">
                  <use xlink:href="#tablet"></use>
                </svg>
              </div>
              <div class="ability__item-img__phone">
                <svg viewBox="0 0 74 131">
                  <use xlink:href="#phone"></use>
                </svg>
              </div>
            </div>
            <div class="ability__item-info">
              <div class="ability__item-info_title">
                <div class="title">Adaptive Layout</div>
                <div class="title__note">&nbsp; По умолчанию в проекте</div>
              </div>
              <div class="ability__item-info_text description">
                Adaptive Layout (Адаптивная вёрстка) - Это такая верстка, при
                которой сайт отлично отображается на различных устройствах:
                компьютерах, планшетах, смартфонах.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="works">
      <a class="works__item" href="#">
        <img src="../assets/example1.jpg" alt="" />
        <div class="works__item-choose">
          <svg viewBox="0 0 100 100" display="none">
            <use xlink:href="#eye"></use>
          </svg>
        </div>
      </a>
      <a class="works__item" href="#">
        <img src="../assets/example2.jpg" alt="" />
        <div class="works__item-choose">
          <svg viewBox="0 0 100 100" display="none">
            <use xlink:href="#eye"></use>
          </svg>
        </div>
      </a>
      <a class="works__item" href="#">
        <img src="../assets/example1.jpg" alt="" />
        <div class="works__item-choose">
          <svg viewBox="0 0 100 100" display="none">
            <use xlink:href="#eye"></use>
          </svg>
        </div>
      </a>
      <a class="works__item" href="#">
        <img src="../assets/example2.jpg" alt="" />
        <div class="works__item-choose">
          <svg viewBox="0 0 100 100" display="none">
            <use xlink:href="#eye"></use>
          </svg>
        </div>
      </a>
      <a class="works__item" href="#">
        <img src="../assets/example2.jpg" alt="" />
        <div class="works__item-choose">
          <svg viewBox="0 0 100 100" display="none">
            <use xlink:href="#eye"></use>
          </svg>
        </div>
      </a>
      <a class="works__item" href="#">
        <img src="../assets/example1.jpg" alt="" />
        <div class="works__item-choose">
          <svg viewBox="0 0 100 100" display="none">
            <use xlink:href="#eye"></use>
          </svg>
        </div>
      </a>
      <a class="works__item" href="#">
        <img src="../assets/example2.jpg" alt="" />
        <div class="works__item-choose">
          <svg viewBox="0 0 100 100" display="none">
            <use xlink:href="#eye"></use>
          </svg>
        </div>
      </a>
      <a class="works__item" href="#">
        <img src="../assets/example1.jpg" alt="" />
        <div class="works__item-choose">
          <svg viewBox="0 0 100 100" display="none">
            <use xlink:href="#eye"></use>
          </svg>
        </div>
      </a>
    </div>
    <div class="service">
      <div class="wrapper">
        <div class="service__content">
          <div class="service__title">Приложение или сайт?</div>
          <div class="service__text description">
            Веб-сайт является источником информации, в то время как<br />
            веб-приложение работает в интерактивном режиме. Функции, задачи,
            пользовательский интерфейс веб-приложения гораздо сложнее.
            Веб-приложение может быть составной частью сайта либо отдельным
            ресурсом. Веб-приложение является более ресурсоемким, так как может
            взаимодействовать с пользователем и выполнять различные действия.
            Более того, если вы ищите решение для вашего онлайн бизнеса, вам
            важно понимать эту разницу.

            <div class="service__text description_black">
              Поскольку вы заинтересованы в этих услугах или вам нужна
              консультация для Вашего e-commerce решения, заполните форму по
              ссылке и я вскорее свяжусь с Вами!
            </div>
          </div>

          <div class="service__form">
            <div class="service__form-inputs">
              <label>
                <input type="text" placeholder="Ваше имя" />
              </label>
              <label>
                <input type="text" placeholder="Ваш e-mail" />
              </label>
            </div>

            <textarea placeholder="Сообщение"></textarea>
            <a href="" class="btn">Отправить</a>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer">
      <div class="wrapper">
        <div class="footer__content">
          <div class="footer__info">
            <div class="footer__info-name">Машталер Богдан</div>
            <div class="footer__info-rigths">
              &copy;2020. Все права защищены.
            </div>
          </div>
          <div class="footer__links">
            <a href="" class="footer__links-link">
              <svg viewBox="0 0 512 512">
                <use xlink:href="#telegram"></use>
              </svg>
            </a>
            <a href="" class="footer__links-link">
              <svg viewBox="0 0 24 24">
                <use xlink:href="#github"></use>
              </svg>
            </a>
            <a href="" class="footer__links-link">
              <svg viewBox="0 0 1691 1407">
                <use xlink:href="#mail"></use>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </footer>
    <div class="sprite">
      <svg
        id="phone"
        width="74"
        height="131"
        viewBox="0 0 74 131"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M63.2193 130.001H10.4924C7.83786 130.03 5.27984 129.005 3.3791 127.149C1.47836 125.292 0.389981 122.757 0.35257 120.098V9.90298C0.389981 7.24426 1.47836 4.70888 3.3791 2.85265C5.27984 0.996413 7.83786 -0.0292048 10.4924 0.000633288H63.2193C65.8738 -0.0292048 68.4318 0.996413 70.3325 2.85265C72.2332 4.70888 73.3216 7.24426 73.359 9.90298V120.098C73.3216 122.757 72.2332 125.292 70.3325 127.149C68.4318 129.005 65.8738 130.03 63.2193 130.001V130.001ZM10.4924 4.06313C8.91348 4.03315 7.387 4.63073 6.24687 5.72513C5.10673 6.81954 4.44574 8.32169 4.40848 9.90298V120.098C4.44574 121.68 5.10673 123.182 6.24687 124.276C7.387 125.371 8.91348 125.968 10.4924 125.938H63.2193C64.7981 125.968 66.3246 125.371 67.4647 124.276C68.6049 123.182 69.2659 121.68 69.3031 120.098V9.90298C69.2659 8.32169 68.6049 6.81954 67.4647 5.72513C66.3246 4.63073 64.7981 4.03315 63.2193 4.06313H10.4924Z"
          fill="#34547A"
        />
        <path
          d="M48.0602 12.1879H25.6513C22.8831 12.1879 20.6321 9.57773 20.6321 6.37851V2.5293H24.688V6.37851C24.688 7.39414 25.266 8.12539 25.6513 8.12539H48.0602C48.4456 8.12539 49.0235 7.42461 49.0235 6.37851V3.15898H53.0794V6.37851C53.0794 9.57773 50.8284 12.1879 48.0602 12.1879Z"
          fill="#34547A"
        />
      </svg>
      <svg
        id="tablet"
        width="108"
        height="130"
        viewBox="0 0 108 130"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M96.34 118.181H11.1685V11.8808H96.3381L96.34 118.181ZM50.3823 124.244C50.3823 122.498 51.8902 121.085 53.7518 121.085C55.6154 121.085 57.1243 122.499 57.1243 124.244C57.1243 125.997 55.6164 127.412 53.7518 127.412C51.8921 127.412 50.3823 125.995 50.3823 124.244ZM107.348 4.99062H107.342C107.342 4.94751 107.348 4.90715 107.348 4.86404C107.348 2.17749 105.028 0 102.164 0C102.118 0 102.074 0.0036689 102.028 0.00550334V0H5.47996V0.00550334C5.435 0.0036689 5.39103 0 5.34412 0C2.4808 0 0.160828 2.17749 0.160828 4.86496C0.160828 4.90807 0.166691 4.94842 0.167668 4.99153H0.160828V124.71H0.299596C0.298619 124.757 0.289824 124.798 0.289824 124.842C0.289824 127.523 2.60491 129.695 5.46334 129.695C5.5083 129.695 5.55325 129.69 5.5982 129.688V129.695H101.915V129.688C101.961 129.69 102.004 129.695 102.052 129.695C104.908 129.695 107.226 127.523 107.226 124.842C107.226 124.798 107.218 124.757 107.215 124.71H107.353L107.348 4.99062Z"
          fill="#34547A"
        />
      </svg>
      <svg
        id="desktop"
        width="150"
        height="130"
        viewBox="0 0 150 130"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill-rule="evenodd"
          clip-rule="evenodd"
          d="M136.19 100.75H91.4259C93.3552 111.478 99.7691 118.859 105.697 123.5H113.492C115.285 123.5 116.735 124.953 116.735 126.75C116.735 128.547 115.285 130 113.492 130H35.6689C33.8757 130 32.4263 128.547 32.4263 126.75C32.4263 124.953 33.8757 123.5 35.6689 123.5H43.4609C49.3852 118.859 55.8056 111.478 57.7317 100.75H12.9705C5.80754 100.75 0 94.9293 0 87.75V13C0 5.82075 5.80754 0 12.9705 0H136.19C143.353 0 149.161 5.82075 149.161 13V87.75C149.161 94.9293 143.353 100.75 136.19 100.75ZM53.1693 123.5H95.9882C90.8162 118.033 86.2117 110.578 84.772 100.75H64.3856C62.9459 110.578 58.3413 118.033 53.1693 123.5ZM142.676 13C142.676 9.412 139.77 6.5 136.19 6.5H12.9705C9.39065 6.5 6.48525 9.412 6.48525 13V74.75H142.676V13ZM142.676 81.25H6.48525V87.75C6.48525 91.338 9.39065 94.25 12.9705 94.25H58.3673H90.7935H136.19C139.77 94.25 142.676 91.338 142.676 87.75V81.25ZM74.5804 91C72.7872 91 71.3378 89.5472 71.3378 87.75C71.3378 85.9528 72.7872 84.5 74.5804 84.5C76.3736 84.5 77.823 85.9528 77.823 87.75C77.823 89.5472 76.3736 91 74.5804 91Z"
          fill="#34547A"
        />
      </svg>
      <svg
        id="web-app"
        width="151"
        height="126"
        viewBox="0 0 151 126"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M101.06 108.939C100.283 108.511 99.6058 107.936 99.0674 107.239C98.8188 106.918 98.6087 106.578 98.4347 106.227H10.1034V27.2964H130.001V78.8353C132.56 79.0449 134.708 80.5689 135.609 82.6559C136.408 82.2592 137.298 82.014 138.233 81.9392C138.866 81.8893 139.494 81.925 140.104 82.0341V7.63312C140.104 3.4242 136.327 0 131.685 0H8.41935C3.77706 0 0 3.4242 0 7.63312V107.754C0 111.963 3.77706 115.387 8.41935 115.387H100.293C99.5761 114.071 99.4061 112.585 99.828 111.155C100.071 110.333 100.492 109.583 101.06 108.939ZM120.755 12.8175C120.755 11.261 122.147 9.99894 123.864 9.99894H126.972C128.689 9.99894 130.081 11.2607 130.081 12.8175V16.0118C130.081 17.5683 128.689 18.83 126.972 18.83H123.864C122.146 18.83 120.755 17.5683 120.755 16.0118V12.8175ZM106.299 12.8175C106.299 11.261 107.691 9.99894 109.408 9.99894H112.517C114.234 9.99894 115.626 11.2607 115.626 12.8175V16.0118C115.626 17.5683 114.234 18.83 112.517 18.83H109.408C107.691 18.83 106.299 17.5683 106.299 16.0118V12.8175ZM91.8434 12.8175C91.8434 11.261 93.2355 9.99894 94.952 9.99894H98.0607C99.7779 9.99894 101.17 11.2607 101.17 12.8175V16.0118C101.17 17.5683 99.7779 18.83 98.0607 18.83H94.952C93.2355 18.83 91.8434 17.5683 91.8434 16.0118V12.8175Z"
          fill="#34547A"
        />
        <path
          d="M149.995 103.564L149.061 98.7611C148.934 98.1143 148.255 97.6823 147.54 97.7963L142.829 98.549C142.264 97.3458 141.541 96.2188 140.684 95.1873L143.761 91.8618C143.985 91.6209 144.094 91.3084 144.064 90.9939C144.033 90.6794 143.866 90.3892 143.599 90.1862L139.479 87.0512C139.213 86.8484 138.867 86.75 138.521 86.7775C138.174 86.805 137.854 86.9563 137.63 87.1979L134.556 90.5207C133.294 89.9378 131.944 89.4883 130.529 89.1916V84.8544C130.529 84.1976 129.942 83.6646 129.217 83.6646H123.837C123.113 83.6646 122.525 84.1976 122.525 84.8544V89.1916C121.11 89.4879 119.761 89.9378 118.499 90.5207L115.423 87.1982C114.958 86.6949 114.13 86.6295 113.575 87.0515L109.454 90.1862C109.188 90.3892 109.021 90.6794 108.99 90.9939C108.96 91.3084 109.069 91.6212 109.292 91.8628L112.37 95.1876C111.514 96.2188 110.79 97.3465 110.225 98.5493L105.513 97.7963C104.801 97.6826 104.12 98.1143 103.993 98.7611L103.06 103.564C102.999 103.875 103.077 104.194 103.276 104.453C103.477 104.711 103.78 104.887 104.123 104.942L108.838 105.695C108.915 107.02 109.169 108.301 109.578 109.521L105.434 111.689C105.133 111.846 104.913 112.106 104.823 112.411C104.733 112.716 104.78 113.04 104.954 113.314L107.644 117.537C107.817 117.81 108.104 118.01 108.44 118.091C108.552 118.118 108.666 118.132 108.78 118.132C109.008 118.132 109.234 118.078 109.435 117.972L113.583 115.801C114.558 116.749 115.659 117.588 116.862 118.298L115.225 122.377C115.106 122.673 115.121 123 115.268 123.286C115.416 123.572 115.682 123.793 116.009 123.901L121.063 125.568C121.208 125.616 121.36 125.641 121.512 125.641C121.701 125.641 121.892 125.604 122.067 125.529C122.382 125.396 122.626 125.155 122.745 124.858L124.382 120.78C125.084 120.857 125.798 120.896 126.523 120.896C127.248 120.896 127.962 120.856 128.664 120.78L130.302 124.858C130.421 125.155 130.665 125.396 130.98 125.529C131.155 125.603 131.344 125.641 131.535 125.641C131.686 125.641 131.839 125.617 131.984 125.568L137.038 123.901C137.365 123.793 137.631 123.572 137.778 123.286C137.925 123 137.941 122.673 137.822 122.377L136.184 118.299C137.386 117.589 138.487 116.749 139.464 115.802L143.611 117.973C143.812 118.078 144.038 118.132 144.267 118.132C144.38 118.132 144.495 118.118 144.606 118.092C144.943 118.01 145.229 117.81 145.403 117.538L148.092 113.314C148.266 113.041 148.314 112.716 148.224 112.411C148.133 112.107 147.913 111.847 147.612 111.689L143.469 109.521C143.878 108.301 144.132 107.02 144.209 105.696L148.923 104.942C149.266 104.888 149.571 104.712 149.77 104.453C149.977 104.194 150.055 103.875 149.995 103.564ZM126.527 111.196C122.542 111.196 119.311 108.267 119.311 104.654C119.311 101.041 122.543 98.1117 126.527 98.1117C130.513 98.1117 133.744 101.041 133.744 104.654C133.744 108.267 130.513 111.196 126.527 111.196Z"
          fill="#34547A"
        />
        <path
          d="M58.8351 71.0495C58.8351 69.5105 57.8402 68.0968 56.3001 67.4484L42.2053 61.5114L56.3005 55.5737C57.8402 54.9247 58.8351 53.5113 58.8351 51.973V51.8697C58.8351 50.5062 58.0781 49.2545 56.8113 48.5229C56.1104 48.1171 55.2941 47.9023 54.4514 47.9023C53.8162 47.9023 53.1786 48.029 52.6081 48.2693L30.0743 57.7692C28.535 58.4182 27.5408 59.8315 27.5408 61.3695V61.6536C27.5408 63.1896 28.5346 64.602 30.0746 65.2543L52.6106 74.7551C53.1932 74.9996 53.8137 75.1237 54.4546 75.1237C55.2898 75.1237 56.1036 74.9086 56.8113 74.5006C58.0788 73.766 58.8354 72.5153 58.8354 71.1534L58.8351 71.0495Z"
          fill="#34547A"
        />
        <path
          d="M81.0684 38.2223C80.2464 37.2021 78.9242 36.5933 77.5314 36.5933H77.4192C75.5066 36.5933 73.8297 37.7025 73.247 39.3513L58.4003 81.0557C57.9777 82.2599 58.2156 83.5861 59.0365 84.6059C59.8585 85.6254 61.1807 86.2346 62.5735 86.2346H62.6861C64.598 86.2346 66.2738 85.1251 66.8557 83.4766L81.7007 41.7754C82.1272 40.5722 81.8907 39.2441 81.0684 38.2223Z"
          fill="#34547A"
        />
        <path
          d="M110.029 57.769L87.4951 48.2691C86.9264 48.0295 86.2898 47.9028 85.6546 47.9028C84.8122 47.9028 83.9956 48.1169 83.295 48.5221C82.0261 49.255 81.2692 50.5064 81.2692 51.8698V51.9731C81.2692 53.5102 82.2634 54.9239 83.8045 55.5755L97.8989 61.5119L83.8041 67.4486C82.2641 68.097 81.2692 69.5106 81.2692 71.0496V71.1536C81.2692 72.5154 82.0261 73.7659 83.2943 74.501C83.9995 74.9085 84.814 75.1238 85.6503 75.1238C86.2905 75.1238 86.9103 74.9998 87.4969 74.7543L110.032 65.2535C111.571 64.6028 112.564 63.1901 112.564 61.654V61.37C112.563 59.8317 111.569 58.4183 110.029 57.769Z"
          fill="#34547A"
        />
      </svg>
      <svg
        id="landing-page"
        width="141"
        height="104"
        viewBox="0 0 141 104"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M136.311 103.753H4.67979C2.25862 103.753 0.2959 101.972 0.2959 99.7751V4.22507C0.2959 2.02807 2.25862 0.24707 4.67979 0.24707H136.311C138.732 0.24707 140.695 2.02807 140.695 4.22507V99.7621C140.695 101.972 138.732 103.753 136.311 103.753ZM131.927 95.7841V36.7251H9.07801V95.7841H131.927ZM9.06369 8.21607V28.7691H131.927V8.21607H9.06369ZM121.756 18.4991C121.756 16.4841 119.965 14.8591 117.744 14.8591C115.524 14.8591 113.733 16.4841 113.733 18.4991C113.733 20.5141 115.524 22.1391 117.744 22.1391C119.95 22.1391 121.756 20.5141 121.756 18.4991ZM106.125 18.4991C106.125 16.4841 104.335 14.8591 102.114 14.8591C99.8934 14.8591 98.1025 16.4841 98.1025 18.4991C98.1025 20.5141 99.8934 22.1391 102.114 22.1391C104.335 22.1391 106.125 20.5141 106.125 18.4991ZM90.5095 18.4991C90.5095 16.4841 88.7187 14.8591 86.4981 14.8591C84.2775 14.8591 82.4867 16.4841 82.4867 18.4991C82.4867 20.5141 84.2775 22.1391 86.4981 22.1391C88.7044 22.1391 90.5095 20.5141 90.5095 18.4991Z"
          fill="#34547A"
        />
        <path
          d="M124.979 45.1489H55.9255V53.105H124.979V45.1489V45.1489Z"
          fill="#34547A"
        />
        <path
          d="M124.979 60.2681H55.9255V68.2241H124.979V60.2681V60.2681Z"
          fill="#34547A"
        />
        <path
          d="M124.979 74.126H55.9255V82.082H124.979V74.126V74.126Z"
          fill="#34547A"
        />
        <path
          d="M14.8802 83.1871H50.0516V44.8501H14.8802V83.1871ZM44.6362 78.2861H20.2956V49.7641H44.6362V78.2861Z"
          fill="#34547A"
        />
      </svg>
      <svg
        id="eye"
        width="100"
        height="100"
        viewBox="0 0 100 100"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g clip-path="url(#clip0)">
          <path
            d="M86.2534 36.4207C66.1706 16.338 33.4966 16.338 13.4139 36.4207L0 49.8329L13.7466 63.5795C23.7872 73.62 36.9764 78.642 50.1672 78.642C63.3581 78.642 76.5456 73.6217 86.5878 63.5795L100.002 50.1657L86.2534 36.4207ZM84.1976 61.191C65.4324 79.9545 34.9003 79.9545 16.1351 61.191L4.77703 49.8329L15.8024 38.8075C34.5676 20.044 65.0997 20.044 83.8649 38.8075L95.223 50.1657L84.1976 61.191Z"
            fill="white"
          />
          <path
            d="M48.2635 36.436C41.7432 36.436 36.4392 41.7401 36.4392 48.2604C36.4392 49.1928 37.1959 49.9496 38.1284 49.9496C39.0608 49.9496 39.8176 49.1928 39.8176 48.2604C39.8176 43.6033 43.6064 39.8144 48.2635 39.8144C49.1959 39.8144 49.9527 39.0577 49.9527 38.1252C49.9527 37.1928 49.1976 36.436 48.2635 36.436Z"
            fill="white"
          />
          <path
            d="M49.9527 27.99C37.8446 27.99 27.9932 37.8413 27.9932 49.9494C27.9932 62.0576 37.8446 71.9089 49.9527 71.9089C62.0608 71.9089 71.9121 62.0576 71.9121 49.9494C71.9121 37.8413 62.0625 27.99 49.9527 27.99ZM49.9527 68.5305C39.7078 68.5305 31.3716 60.1944 31.3716 49.9494C31.3716 39.7045 39.7078 31.3684 49.9527 31.3684C60.1976 31.3684 68.5338 39.7045 68.5338 49.9494C68.5338 60.1944 60.1993 68.5305 49.9527 68.5305Z"
            fill="white"
          />
        </g>
        <defs>
          <clipPath id="clip0">
            <rect width="100" height="100" fill="white" />
          </clipPath>
        </defs>
      </svg>
      <svg
        id="telegram"
        height="512px"
        style="enable-background: new 0 0 512 512"
        version="1.1"
        viewBox="0 0 512 512"
        width="512px"
        xml:space="preserve"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
      >
        <g id="comp_x5F_335-telegram">
          <g>
            <path
              d="M484.689,98.231l-69.417,327.37c-5.237,23.105-18.895,28.854-38.304,17.972L271.2,365.631l-51.034,49.086    c-5.647,5.647-10.372,10.372-21.256,10.372l7.598-107.722L402.539,140.23c8.523-7.598-1.848-11.809-13.247-4.21L146.95,288.614    L42.619,255.96c-22.694-7.086-23.104-22.695,4.723-33.579L455.423,65.166C474.316,58.081,490.85,69.375,484.689,98.231z"
            />
          </g>
        </g>
        <g id="Layer_1" />
      </svg>
      <svg
        id="github"
        enable-background="new 0 0 24 24"
        height="24px"
        version="1.1"
        viewBox="0 0 24 24"
        width="24px"
        xml:space="preserve"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
      >
        <path
          d="M15.5,22.7c0,0-0.1,0-0.1,0l-0.1-0.1l0-0.6c0-0.6,0-1.5,0-2.5c0-0.7-0.1-1.3-0.4-1.8c2.3-0.4,4.8-1.6,4.8-6.1  c0-1.2-0.4-2.3-1.1-3.2c0.2-0.6,0.3-1.7-0.2-3.1c-0.1-0.1-0.2-0.2-0.3-0.3c0,0-0.2-0.1-0.4-0.1c-0.6,0-1.5,0.2-3,1.2  C13.9,6,13,5.8,12,5.8c-1,0-1.9,0.1-2.8,0.3C7.8,5.2,6.8,5,6.2,5C6,5,5.9,5.1,5.8,5.1c-0.1,0-0.3,0.2-0.3,0.3C5,6.8,5.1,7.9,5.3,8.5  c-0.7,0.9-1.1,2-1.1,3.2c0,4.4,2.6,5.6,4.8,6.1c-0.1,0.2-0.2,0.5-0.3,0.8c-0.2,0.1-0.5,0.2-0.9,0.2c-0.4,0-0.8-0.1-1.1-0.4  c0,0-0.1-0.1-0.1-0.1c0,0,0,0,0,0c-0.1-0.1-0.1-0.2-0.2-0.2c0,0,0,0,0,0c0,0,0,0,0,0l-0.1-0.1c0,0-0.1-0.1-0.1-0.1  c0-0.1-0.8-1.3-2.2-1.4c-0.5,0-0.9,0.2-1,0.5c-0.2,0.5,0.4,0.9,0.7,1.1c0,0,0.6,0.3,1,1.4c0.2,0.7,1.1,2,3.2,2c0.2,0,0.4,0,0.7,0  l0,1.4l-0.1,0.1c0,0-0.1,0,0,0C4,21.2,1,17,1,12.3c0-6.1,4.9-11,11-11s11,4.9,11,11C23,17,20,21.2,15.5,22.7z"
        />
      </svg>
      <svg
        id="mail"
        height="1407px"
        style="enable-background: new 0 0 1691 1407"
        version="1.1"
        viewBox="0 0 1691 1407"
        width="1691px"
        xml:space="preserve"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
      >
        <g id="packet">
          <path
            d="M1691,165.177C1691,73.952,1617.048,0,1525.823,0H165.177C73.952,0,0,73.952,0,165.177v1076.646   C0,1333.048,73.952,1407,165.177,1407h1360.646c91.225,0,165.177-73.952,165.177-165.177V165.177z M166.062,132h1361.057   c18.216,0,32.881,14.528,32.881,32.746v1.433L869.916,856.337c-8.417,8.417-18.208,9.675-23.318,9.675   c-5.11,0-14.934-1.258-23.353-9.675L133,166.085v-1.339C133,146.528,147.846,132,166.062,132z M1527.119,1275H166.062   c-18.216,0-33.062-15.084-33.062-33.301V352.961l596.826,596.816c31.198,31.197,72.684,48.376,116.803,48.376   c44.125-0.003,85.528-17.186,116.724-48.382L1560,353.054v888.645C1560,1259.916,1545.335,1275,1527.119,1275z"
          />
        </g>
        <g id="Layer_1" />
      </svg>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainWrap",
  data() {
    return {
      isActive: false,
    };
  },
  methods: {
    showBurger() {
      this.isActive = !this.isActive;
    },
  },
};
</script>

<style lang="scss">
.wrapper {
  max-width: 1140px;
  margin: 0 auto;
}
.welcome {
  background: #eeeff1;
  height: 100vh;
  padding-bottom: 100px;

  .nav {
    display: flex;
    justify-content: space-between;
    padding: 30px 30px 0 30px;
    &__logo {
      width: 50px;
    }
    &__links {
      display: flex;
      align-items: center;
      a {
        text-decoration: none;
        justify-content: space-around;
        color: #000000;
        padding: 10px 20px;
        text-transform: uppercase;

        font-size: 16px;
        transition: 0.3s;
      }
      a:hover {
        color: #34547a;
      }
      &__burger {
        display: none;
      }
    }
  }
  &__content {
    margin: 155px 0 0 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  &__image {
    margin-right: 130px;
    width: 280px;
  }
  &__info {
    &-title {
      margin-bottom: 50px;
      color: #000000;
      font-size: 40px;
      font-weight: 500;
      text-transform: uppercase;
    }
    &-text {
      margin-bottom: 60px;
    }
    &-button {
      a {
        text-decoration: none;
        padding: 25px 40px;
        background: #34547a;
        color: #ffffff;
        text-transform: uppercase;
        transition: 0.3s;
      }
      a:hover {
        background: #1b416e;
      }
    }
  }
}
.about {
  &__content {
    display: flex;
    justify-content: space-between;
    margin: 100px 0;
    align-items: center;
  }
  &__skills {
    width: 100%;
    &-title {
      font-weight: 500;
      font-size: 32px;
      margin-bottom: 50px;
    }
    &-text {
      color: #34547a;
      font-size: 18px;
      &__skill {
        position: relative;
        padding-bottom: 20px;
        margin-bottom: 30px;
        border-bottom: 4px solid #c4c4c4;
      }
      &__skill::before {
        content: "";
        position: absolute;
        bottom: -4px;
        height: 4px;
        width: 75%;
        background: #34547a;
      }
    }
  }
  &__img {
    width: 500px;
    margin-left: 150px;
    border-radius: 15px;
  }
}

.ability {
  background: #eeeff1;
  &__content {
    padding: 100px 0;
  }
  &__title {
    text-align: center;
    font-weight: 500;
    font-size: 32px;
    margin-bottom: 100px;
  }
  &__item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 50px;

    &:hover {
      .ability__item-img__tablet {
        opacity: 1;
      }
      .ability__item-img__phone {
        opacity: 1;
      }
      .title__note {
        opacity: 1;
      }
    }
    &-img {
      margin-left: 100px;
      display: flex;
      align-items: center;
      svg {
        fill: #34547a;
        height: 100%;
      }
      &__landing-page {
        width: 120px;
      }
      &__web-app {
        width: 130px;
      }
      &__desktop {
        height: 110px;
      }
      &__tablet {
        transition: 1s;
        opacity: 0;
        height: 110px;
        margin-left: 30px;
      }
      &__phone {
        transition: 1s;
        opacity: 0;
        height: 110px;
        margin-left: 30px;
      }
    }
    &-info {
      width: 50%;
      &_title {
        margin-bottom: 30px;
        display: flex;
        align-items: flex-end;
        font-size: 32px;
        font-weight: 500;
      }
      &_text {
      }
    }
  }
}
.works {
  display: flex;
  flex-wrap: wrap;
  &__item {
    display: block;
    width: 25%;
    position: relative;
    padding-bottom: 25%;
    &:hover {
      .works__item-choose {
        background: #4670a3;
        opacity: 80%;
      }
    }
    img {
      height: 100%;
      width: 100%;
      object-fit: cover;
      position: absolute;
      top: 0;
      left: 0;
    }
    &-choose {
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      position: absolute;
      top: 0;
      left: 0;
      transition: 0.3s;
      opacity: 0;
      svg {
        display: block;
        width: 100px;
        transition: 0.3s;
      }
    }
  }
}
.service {
  background: #eeeff1;
  margin: 0 auto 0;

  &__content {
    padding: 100px 300px;
    text-align: center;
  }
  &__title {
    margin-bottom: 50px;
    font-weight: 500;
    font-size: 32px;
    text-transform: uppercase;
  }
  &__text {
    margin-bottom: 65px;
  }
  &__form {
    &-inputs {
      display: flex;
      justify-content: space-between;
      margin-bottom: 20px;
    }
    label {
      width: calc(50% - 15px);
    }
    input,
    textarea {
      width: 100%;
      height: 55px;
      padding: 3px 20px 0;
      font-size: 16px;
      border: none;
      font-family: "Roboto", sans-serif;

      &::placeholder {
        color: #5f5d5d;
      }
      &:focus {
        outline: none;
      }
    }
    textarea {
      height: 175px;
      padding: 20px;
      resize: none;
      margin-bottom: 50px;
    }
  }
}
.footer {
  background: #34547a;
  padding: 40px 0;
  &__content {
    display: flex;
    justify-content: space-between;
  }
  &__info {
    color: #ffffff;
    font-weight: 500;
    font-size: 21px;
    &-rigths {
      margin-top: 20px;
      font-size: 13px;
    }
  }
  &__links {
    display: flex;
    align-items: center;

    &-link {
      display: flex;
      margin-left: 20px;
      width: 35px;
      height: 35px;
      svg {
        width: 100%;
        fill: #ffffff;
      }
      &:hover {
        svg {
          fill: #558dfd;
        }
      }
    }
  }
}
@media screen and (max-width: 1440px) {
  .wrapper {
    max-width: 1024px;
  }
}
@media screen and (max-width: 1023px) {
  .wrapper {
    max-width: 768px;
  }
  .nav {
    &__links {
      a {
        font-size: 14px;
      }
    }
  }
  .welcome {
    padding-bottom: 50px;
    &__content {
      margin: 70px 0 0 70px;
    }

    &__image {
      margin-right: 100px;
    }
    &__info {
      &-title {
        font-weight: 500;
        font-size: 32px;
      }
      &-text {
      }
      &-button {
        a {
          padding: 20px 35px;
          font-size: 15px;
        }
      }
    }
  }
  .about {
    &__img {
      width: 440px;
    }
  }
  .wrapper {
  }
  .service {
    &__content {
      padding: 100px 95px;
    }
  }
  .footer {
    padding: 30px;

    &__info {
      &-name {
        font-size: 16px;
      }
      &-rigths {
        font-size: 12px;
      }
    }
  }
}
@media screen and (max-width: 767px) {
  .wrapper {
    width: 100%;
    max-width: 425px;
  }
  .description {
    font-size: 12px;
  }

  .welcome {
    padding: 0;
    &__content {
      margin: 0px 20px 0;
      display: block;
      text-align: center;
      position: relative;
    }
    .nav {
      padding: 15px 30px 10px 30px;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 12;
      background: #eeeff1;

      &__logo {
        width: 50px;
      }
      &__links {
        display: block;
        position: fixed;
        width: auto;
        z-index: 10;
        right: -500px;
        top: 77px;
        overflow: hidden;
        transition: 0.6s;
        &.active {
          right: 0;
        }
        &-link {
          display: block;
          border: 2px solid #042f70;
          margin-top: 2px;
          background: #eeeff1;
        }
      }
      &__burger {
        display: block;
        width: 40px;
        height: 40px;
        position: relative;
        span {
          position: absolute;
          display: block;
          width: 100%;
          height: 4px;
          background: #34547a;
          border-radius: 5px;
          transition: 0.3s;
          &:nth-child(1) {
            top: 7px;
          }
          &:nth-child(2) {
            top: 50%;
            transform: translateY(-50%);
            transition: 0.2s;
          }
          &:nth-child(3) {
            bottom: 7px;
          }
        }
        &.active {
          span {
            &:nth-child(1) {
              top: 50%;
              transform: translateY(-50%) rotate(45deg);
            }
            &:nth-child(2) {
              opacity: 0;
            }
            &:nth-child(3) {
              top: 50%;
              transform: translateY(-50%) rotate(-45deg);
            }
          }
        }
      }
    }
    &__image {
      width: 130px;
      margin: 140px auto 20px;
    }

    &__info {
      &-title {
        font-size: 20px;
        margin-bottom: 20px;
      }
      &-text {
        margin-bottom: 30px;
      }
      &-button a {
        padding: 12px 20px;
        font-size: 12px;
      }
    }
  }

  .about {
    &__content {
      margin: 60px 20px 40px;
      position: relative;
    }
    &__skills {
      &-title {
        margin-bottom: 40px;
      }
      &-text {
        font-size: 15px;
        &__skill {
          margin-bottom: 40px;
        }
      }
    }
    &__img {
      display: block;
      position: absolute;
      top: -25px;
      right: 0;
      border-radius: 100px;
      width: 110px;
    }
  }
  .ability {
    &__content {
      padding: 50px 20px 50px;
    }

    &__title {
      margin-bottom: 40px;
      display: flex;
    }

    &__item {
      display: block;
      align-items: center;
      margin-bottom: 50px;
      position: relative;

      &-img {
        position: absolute;
        align-items: baseline;
        top: 0;
        right: 15px;
        margin-left: 0;
        &__landing-page {
          width: 70px;
        }
        &__web-app {
          width: 75px;
        }
        &__desktop {
          height: 55px;
        }
        &__tablet {
          opacity: 1;
          height: 45px;
          margin-left: 5px;
        }
        &__phone {
          opacity: 1;
          height: 35px;
          margin-left: 5px;
        }
      }
      &-info {
        width: 100%;
        &_title {
          font-weight: 500;
          font-size: 28px;
          width: 55%;
          margin-bottom: 35px;
        }

        &_text {
        }
      }
      .title__note {
        display: none;
      }
    }
  }
  .service {
    &__content {
      padding: 50px 20px;
    }

    &__title {
      font-size: 28px;
      margin-bottom: 30px;
    }

    &__text {
      font-weight: 500;
      margin-bottom: 30px;
    }

    input,
    textarea {
      font-size: 12px;
    }
    a {
      padding: 14px 28px;
      font-size: 12px;
    }
  }
  .footer {
    padding: 10px 20px;
    &__content {
    }

    &__info {
      align-items: center;
      &-name {
        font-size: 10px;
        margin-top: 5px;
      }

      &-rigths {
        margin-top: 4px;
        font-size: 10px;
      }
    }

    &__links {
      &-link {
        margin-left: 10px;
        width: 20px;
      }
    }
  }
}
</style>
