# Telegina Elena

## Contact Information
- **Location:** Russian, Ekaterinburg
- **Email:** letelegina@mail.ru
- **Telegram:** @LeTelegina
- **GitHub:** [letelegina](https://github.com/LeTelegina)
- **Discord:** [letelegina](https://discordapp.com/users/916930436431753246)

## About Me
Currently working as a system engineer in a provider company. I am involved in the operation of a number of user services.

I am fond of web design, develop sites from scratch and collect them on constructors, if necessary, add functionality code. I want to better understand the frontend development that would make their sites more functional and possibly coordinately change the direction of its activities.

## Skills
- Linux (Debian, Ubuntu)
- Figma, VSCode
- Git, GitHub, Bitbucket
- Basic: HTML/CSS, JavaScript

## Code Example
```
$(document).ready(function() {
  function updateOverflow() {
    if ($(window).width() < 980) {
      $('.rec654547484, .rec654544000, .rec654550587').css('overflow', 'hidden');
    } else {
      $('.rec654547484, .rec654544000, .rec654550587').css('overflow', 'auto'); 
    }
  }
  
  $(window).resize(updateOverflow);
  updateOverflow();

  $('.slidebtn a').click(function() {
    var $target = $(this).attr('href').slice(1);

    if ($('.uc-' + $target).is(':visible')) {
      $('.uc-' + $target).fadeOut(0);
      $(this).removeClass('bactive');
    } else {
      $('[class*="uc-slide"]').fadeOut(0);
      $('.uc-' + $target).fadeIn(0); 
      $('.slidebtn a').removeClass('bactive');
      $(this).addClass('bactive');
    }
    t_lazyload_update();
  });

  $('[class*="uc-slide"]').not('.uc-slide2').fadeOut(0);
  $('[href="#slide2"]').addClass('bactive'); 
  $('.uc-slide2').fadeIn(0); 
});
```

## Experience
Realization of additional functionality for sites implemented on the Tilda constructor: accordions, slider, page switcher, base animation, etc.

Examples of sites:  [Holy Guns](https://dom-uyta.ru), [Dom Yyta](https://dom-uyta.ru), [Dom Yyta - Lendinf](https://design.dom-uyta.ru)

## Education
### UX/UI Designer
Trained at UpRock School of Design in 2021 as a UX/UI designer.

### Front-end development
Self-study of frontend development on various free courses and youtube

## Languages
- Russian, native speaker
- English (A1), reading technical literature