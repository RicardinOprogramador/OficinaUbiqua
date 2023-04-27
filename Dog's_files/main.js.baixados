
const showMneu = (toggleId, navId) => {
    const toggle = document.getElementById(toggleId),
        nav = document.getElementById(navId)

    if (toggle && nav) {

        toggle.addEventListener('click', () => {

            nav.classList.toggle('show-menu')
        })
    }
}
showMneu('nav-toggle', 'nav-menu')


const navLink = document.querySelectorAll('.nav__link')
function linkAction() {
    const navMenu = document.getElementById('nav-menu')

    navMenu.classList.remove('show-menu')
}
navLink.forEach(n => n.addEventListener('click', linkAction))


const linkColor = document.querySelectorAll('.nav__link')

function colorLink() {
    if (linkColor) {
        linkColor.forEach(L => L.classList.remove('active-link'))
        this.classList.add('active-link')
    }
}

linkColor.forEach(L => L.addEventListener('click', colorLink))


function scrollHeader() {
    const scrollHeader = document.getElementById('header');

    if (this.scrollY >= 200) scrollHeader.classList.add('scroll-header'); else scrollHeader.classList.remove('scroll-header')
}
window.addEventListener('scroll', scrollHeader)


function scrollTop() {
    const scrollTop = document.getElementById('scroll-top');

    if (this.scrollY >= 560) scrollTop.classList.add('scroll-top'); else scrollTop.classList.remove('scroll-top')
}
window.addEventListener('scroll', scrollTop)