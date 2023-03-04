# Лабараторная работа 1

## Задание 1 

```
head
    head__hair
    head__eye_left
    head__eye_right
    head__nose_crooked
    head__mouth_small
torso
    torso__hair_black
    torso__breast
    torso__navel
left-arm
    left-arm__wrist
        left-arm__finger
        left-arm__finger
        left-arm__finger
        left-arm__finger
        left-arm__finger
right-arm
    left-arm__finger
        right-arm__finger
        right-arm__finger_ring
        right-arm__finger
        right-arm__finger
        right-arm__finger
left-leg
    left-leg__knee
    left-leg__feet
        left-leg__finger
        left-leg__finger
        left-leg__finger
        left-leg__finger
        left-leg__finger
right-leg
    right-leg__knee
    right-leg__feet
        right-leg__finger
        right-leg__finger
        right-leg__finger
        right-leg__finger
        right-leg__finger
```        

## Задание 2

### header
![header](/img/header.jpg)

```
header.header>(a.header__img-link>img.header__logo)+nav.header__navigation>ul.header__list>li.header__item>a.header__link*5+li.header__link_colored
```

### footer
![footer](/img/footer1.jpg)

```
footer.footer>a.footer__img-link>img.footer__img+(ul.footer__list>(li.footer__list.footer__list-item_heading>a.footer__heading-link)+(li.footer__list-item>a.footer__link)*8)*3+.footer__copyrite-block>p.footer__copyrite-text+a.footer__link
```

### form
![form](/img/form.jpg)

```
section.sign-up>p.sign-up__discription+h2.sign-up__heading+form.form>(label.form__label>input.form__input)+button.form__button

```

### insights
![insights](/img/insights.jpg)

```
section.insights>h2.insights__heading+ul.insights__container>li.insight(img.insight__photo+h3.insight__name+p.insight__discription+p.insight__date)*3

```