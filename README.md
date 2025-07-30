# 🌆 Background Slider на Swiper.js

Этот проект представляет собой полноэкранный слайдер с эффектом Cube от библиотеки **Swiper.js**, с анимированными названиями городов, наложенными поверх фоновых изображений. Каждое название города стилизовано с использованием `background-clip: text` и анимацией фона. Основной акцент сделан на визуальные эффекты и плавность переходов.

## ⚙️ Технологии
- HTML5
- CSS3 (анимированный текст, фильтры, Flexbox)
- [Swiper.js ](https://swiperjs.com/)
- JavaScript (минимальное подключение)

## 🖼️ Города в слайдере
- **Edinburgh**
- **Stockholm**
- **Paris**
- **Brugge**
- **Bavaria**
- **Copenhagen**

**CSS стиль для текста:**
.seven {
  -webkit-text-stroke: 1px rgba(0, 150, 255, 0.9);
  background: url(https://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/Flag_of_Kyiv.svg/1280px-Flag_of_Kyiv.svg.png);
  background-size: cover;
  background-repeat: repeat;
  -webkit-background-clip: text;
}

## 📁 Файлы проекта

* `index.html` — основная структура
* `style.css` — стили, включая анимацию текста
* `module.js` — инициализация Swiper
