1.

let profImage2 = document.querySelector('.profile-image')

profImage2.src = "http://static1.squarespace.com/static/52c2df7ae4b0d215dded86fd/536fab69e4b00b0fd2515399/584cbe492e69cf27ac238169/1499478450297/eWP-59dw_400x400.jpg?format=1500w"

2.

let skyImage = document.querySelector('#left-image img')

skyImage.src = "https://i.ebayimg.com/images/g/ycAAAOSwoudW4wYE/s-l300.jpg"
"https://i.ebayimg.com/images/g/ycAAAOSwoudW4wYE/s-l300.jpg"

3.

let employmentDisc = document.querySelector('#employment .info-title')

employmentDisc.innerText = 'CHANGED TO THIS!'

4.

let body = document.querySelector('body')
body.style.backgroundColor = 'grey'

5.

let highlightClass = document.querySelectorAll('.highlight');

for(let i = 0; i < highlightClass.length; i++) {
    highlightClass[i].style.color = 'blue';
}

6.

$('h1').css('fontFamily', 'monospace')
<!-- let x = document.querySelector('h1') -->

7. 

$('.action-icon-bg').css('backgroundColor', 'blue')

8. 

$('#name').attr('placeholder', 'identify yourself')

9.

$('#message').attr('placeholder', 'state your business')

10.

$('#name').attr('value', 'your nemesis')

11.

$('#email').attr('value', "koalathebear@gmail.com")

12.

$('#submit').attr('value', "En garde!")

13.

$('#submit').attr('disabled', true)

14. 

let x = document.querySelector('.bio-info')
let removex =  aside.removeChild(x)


----------------PART 2----------------

1.

$('div .bar-default:nth-of-type(3)').remove()

<!-- let skill = document.querySelector('#time-travel')
let remove = section.removeChild(skill) -->

2.

let pikachuPic = document.querySelector('#right-image > img') let pikaClone = pikachuPic.cloneNode(true) let picSection = document.querySelector('section > :nth-child(2)') picSection.appendChild(pikaClone)


for (let x = 0; x < 10; x++) { let newPikaClone = document.createElement('img') newPikaClone.src = 'images/pikachu-drawing.jpg' picSection.appendChild(newPikaClone) }




