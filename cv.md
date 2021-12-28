******
# Vladimir Khristoforov
### Contacts:
***
Location: Russia city Armavir

Phone: +79189622223

e-mail: hristick@mail.ru

git: Hristick
***
### About myself
***
I am a switcher from another technical specialty. Took several courses at htmlacademy. I love the frontend and the magic of the web.
### Skills
***
* html/css
* SASS
* BEM
* javaScript
* Photoshop
* Figma
***
```
const isFormValidityGuestCount = function () {
  const guestValue = guestCountFormValue.value;
  const roomsValue = roomsNumberCount.value;
  if (roomsValue === `100`)  {
    roomsNumberCount.setCustomValidity('Данная категория не для гостей!');
    guestCountFormValue.value = 0;
  } else if (roomsValue < guestValue) {
    roomsNumberCount.setCustomValidity('Вас слишком много выберите номер побольше!');
  }   else  {roomsNumberCount.setCustomValidity(``);}

  guestCountFormValue.reportValidity();
}
```
