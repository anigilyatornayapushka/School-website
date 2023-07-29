# School-website

![School](https://image.mel.fm/i/v/v9QK4SCTny/590.png)

For a long time I wanted to create a project on this topic. After a short vacation, I want to consolidate the material covered and master new technologies.

## Functionality

- Create director, teacher and student accounts.
- Account activation, Logging in, Logging out.
- Creation of courses (closed, opened).
- Inviting in courses.
- Posting of materials.
- Posting homeworks of different categories.
- Check homeworks and grading of students.
- View account statistics.
- Change password, Remind password.
- Leave course (students) or delete it (teachers).

## Requirements

1. **Create .env file in root directory and add following values:**

   ```.env
   SECRET_KEY=your project secret key
   DEBUG=TRUE / FALSE
   DB_NAME=name of database
   DB_USER=username
   DB_PASS=user password
   ```

1. **Python**

   Python is a high-level, general-purpose programming language with dynamic strong typing and automatic memory management.

   https://www.python.org/

2. **Libraries**

   ``
   pip install -r tools\requirements\req.txt
   ``

3. **Postgresql**

   PostgreSQL is a powerful, open source object-relational database system with over 35 years of active development that has earned it a strong reputation for reliability, feature robustness, and performance.

   https://www.postgresql.org/

4. **Redis**

   Redis is an open source NoSQL class resident database management system that works with key-value data structures.

   https://redis.io/

5. **RabbitMQ**

   RabbitMQ is a software message broker based on the AMQP standard, a replicable message-oriented middleware.

   https://www.rabbitmq.com/

## Start using

1. Create a director account by next command in powershell.

   ``
   py manage.py createsuperuser
   ``

2. Create a teacher accounts in admin panel in */admin/* route.

3. Invite students.

4. Start teaching.

## License

This project is licensed under the MIT License. You can find the full text of the license [here](LICENSE).
