# Just a simple Laravel for API Server
เรื่องราวมันเกิดจากความว่างที่ต้องนั่งรอขึ้นเครื่องบินประมาณสองชั่วโมง ณ สนามบินนานาชาติดอนเมือง (DMK)

โดยเกิดจากความสงสัยว่า เอ๊ะ! หลังจากเลิกเขียน Laravel มาตั้งนาน แล้วก็ออกมา React + NodeJS + MongoDB ถ่อมาถึง GraphQL เล่น JWT จนสนุกสนาน กินเวลามาก็ 4-5 เดือนแล้ว .. ก็เจออะไรต่างๆ นานาทั้งขัดใจและไม่ขัดใจ ใจเลยคิดว่าถ้ากลับมาเป็น Php + MySQL อย่างที่เคยทำ จะเขียนได้ดีขึ้นไหมนะ ? .. แล้วก็จริงๆ แล้ว เราใช้พลังของ Laravel ไปหมดแล้วจริงๆ หรือ ? .. แล้วถ้า Laravel จะกลายเป็น RESTful API ให้ library เก๋ๆ อย่าง React มันจะทำได้ดีไหมนะ ของจะมีครบไหมนะ ?

เป็นเหตุให้เปิด Docs ของ Laravel แล้วก็อ่าน Blog อีกหลายบทความ จนเกิดเป็น Repository นี้ขึ้นมา

## About the Side-project
พอคิดว่าอยากทำให้มันเข้าใจง่ายๆ เลยคิดว่าถ้าเป็น "ระบบจัดการอีเวนท์" คล้ายๆ Eventpop ที่จะพยายามประยุกค์ใช้ทุกอย่างที่ Laravel ให้มากที่สุด มาเริ่มวาง Todolist กันก่อน ... ถ้าเครียดๆ จากสอบไฟนอล จะมานั่งทำดู

## Todolist
- [ ] Initial Front End with NextJS and Semantic UI.
- [ ] Initial RESTful API with Laravel
  - [ ] Events Model
  - [ ] Users Model
  - [ ] Tickets Model
- [ ] Implement API Authentication
  - [ ] Email/Password Login
  - [ ] Facebook Login
  - [ ] Redis Server
- [ ] Implement Authorization
- [ ] Implement Services
  - [ ] Email Sender
  - [ ] Line Notify
- [ ] Implement Error Handles
  - [ ] Sentry Logging
- [ ] Test it now !
- [ ] Task Scheduling for Daily Ranking
- [ ] 

## References

- [A modern REST API in Laravel 5 Part 0: Introduction](http://esbenp.github.io/2016/04/11/modern-rest-api-laravel-part-0/)
- [A modern REST API in Laravel 5 Part 2: Resource controls](http://esbenp.github.io/2016/04/15/modern-rest-api-laravel-part-2/)
- [A modern REST API in Laravel 5 Part 3: Error handling](http://esbenp.github.io/2017/01/14/modern-rest-api-laravel-part-3/)
- [A modern REST API in Laravel 5 Part 4: Authentication using Laravel Passport](http://esbenp.github.io/2017/03/19/modern-rest-api-laravel-part-4/)
- [HTTP API Design Guide](https://geemus.gitbooks.io/http-api-design/content/en/)
- [HTTP Status Codes](https://httpstatuses.com/)
- [Implementing before/after middleware in PHP](http://esbenp.github.io/2015/07/31/implementing-before-after-middleware/)
- [Domain-Driven Design (DDD) in Domainlanguage.com](https://domainlanguage.com/)
- [Hexagonal Architecture](http://fideloper.com/hexagonal-architecture)

---

> ทั้งหมดใน Repository นี้ หวังอยู่อย่างเดียวมองทุกอย่างให้ลึกลงไป มากกว่าแค่ Route - Controller - Model - View และพยายามให้มันกลายเป็น API Server ที่ดีพอที่คนอื่นที่สนใจจะกลับมาดูมันและต่อยอดได้ฮะผม
