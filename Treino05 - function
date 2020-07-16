const getSleepHours = day => {
switch (day) {
  case 'segunda':
    return 5;
    break;
  case 'terça':
    return 6;
    break;
  case 'quarta':
    return 5;
    break;
  case 'quinta':
    return 4;
    break;
  case 'sexta':
    return 6
    break;
  case 'sábado':
    return 5;
    break;
  case 'domingo':
    return 6;
    break;
}
};
//console.log(getSleepHours('domingo'));
const getActualSleepHours = () => getSleepHours('segunda') + getSleepHours('terça') + getSleepHours('quarta') + getSleepHours('quinta') + getSleepHours('sexta') + getSleepHours('sábado') + getSleepHours('domingo');
const getIdealSleepHours = () => {
  idealHours = 8;
  return idealHours * 7;
}
//console.log(getActualSleepHours());
//console.log(getIdealSleepHours());
const calculateSleepDebt = () => {
  actualSleepHours = getActualSleepHours();
  idealSleepHours = getIdealSleepHours();
  if (actualSleepHours === idealSleepHours) {
    console.log('Suas horas de sono estão perfeitamente equilibradas!');
  } else if (actualSleepHours > idealSleepHours) {
console.log(actualSleepHours);
    console.log('Você já dormiu ' + (actualSleepHours - idealSleepHours) + 'horas a mais! Chega de dormir seu preguiçoso!');
  } else if (actualSleepHours < idealSleepHours) {
console.log('Você precisa dormir um pouco mais, pois está com ' + (idealSleepHours - actualSleepHours)+' horas de sono atrasadas!');
  }
};
calculateSleepDebt();
