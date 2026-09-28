# Web Form Honeypot Bot Trap

This example demonstrates a simple web form honeypot, a technique used to detect and deter automated bots. It includes a hidden input field that legitimate users cannot see or interact with due to CSS. If a bot fills this hidden field, the form submission is identified as a bot attempt, showcasing how spam traps can selectively target automated processes while allowing human interactions to proceed.

## Language

`html`

## How to Run

1. Save the code as `index.html`.
2. Open `index.html` in any web browser.
3. Try submitting the form normally (as a human) and observe the result. To simulate a bot, use your browser's developer tools to remove `display: none;` from the `.honeypot-field` CSS, type something into the now visible "Leave this field empty" input, and submit.

## Original Article

This example accompanies the Turkish article: [Aldatıcı Başarı: Spam Tuzakları Neden Bazen Sadece Sizi Yakalar?](https://fatihsoysal.com/blog/aldatici-basari-spam-tuzaklari-neden-bazen-sadece-sizi-yakalar/).

## License

MIT — see [LICENSE](LICENSE).
