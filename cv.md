## rsschool-cv

# Rubis Irina


# My Contact Info

* Location: Saint-Peterburg, Russia
* Phone: +79602834033
* email: rubis.smm@gmail.com
* GitHub: Rubis-design
* CodePen: Rubis-design


# Summary  

Now I work as a web designer and layout designer on no-code platforms as a freelancer.
I have a higher computer education in the field of information security. But I didn’t work in my specialty for a long time.
I really love to learn and achieve high results in my niche. In my past professional activities, I have repeatedly achieved international awards and statuses.
Now I'm studying front-end development, updating my knowledge acquired at the university and studying new modern tools in development
My main strengths are perseverance, problem solving and quick learning. I want to gain knowledge and skills that will be sufficient for employment in the company.


# Skills

* Basic HTML
* Basic CSS
* Basic JS
* Figma
* other graphics editor app (photoshop, illustration)


# Code example
```
import _ from 'lodash';

const getMenCountByYear = (users) => users
  .filter((user) => user.gender === 'male')
  .map((user) => {
    const year = [];
    year.push(user.birthday.slice(0, 4));
    return year;
  })
  .reduce((acc, year) => {
    const count = _.get(acc, year, 0) + 1;
    return { ...acc, [year]: count };
  }, {});
export default getMenCountByYear;
```

