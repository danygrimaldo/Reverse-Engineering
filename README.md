https://docs.google.com/document/d/18MfLxzPjgZFRdFtZ2hcH5MI9m3HRhsyxviBnGYRlsTQ/edit?usp=sharing

Week 14 : REVERSE ENGINEERING

Passport is a middleware that is available when using express and sequelize to authenticate sensitive login information. It communicates with the database and only allows access if the account is registered within said database. In order to work, Sequelize needs to serialize and deserialize the user to return the proper payload.

