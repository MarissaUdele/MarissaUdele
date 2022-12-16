"const nav = document.createElement('nav');
const links = [  { text: 'Home', url: '/home' },  { text: 'About', url: '/about' },  { text: 'Contact', url: '/contact' }];
links.forEach(link => {
  const a = document.createElement('a');
  a.innerHTML = link.text;
  a.href = link.url;
  nav.appendChild(a);
  nav.innerHTML += ' | ';
});
document.body.appendChild(nav);
"
![image](https://user-images.githubusercontent.com/120653581/208056042-aadbe58f-81fe-4bb0-a3ad-aa9172324cbb.png)
