### Hi there 👋 , I'm [Evgeniy](https://www.github.com/Evgeniy-Golodnykh)

#### I'm a versatile developer, with experience in building web platforms. I like accessibility, performance and robust code.

```python
class WhoAmI:

    def __init__(self):
        self.name = 'Evgeniy Golodnykh'
        self.position = 'Python Developer'
        self.current_work = 'Writing code'
        self.web = 'https://www.github.com/Evgeniy-Golodnykh'
        self.code = {
            'backend': ['Python', 'Django', 'FastAPI'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3'],
            'devops': ['Docker', 'Linux', 'GitHub Actions'],
            'tools': ['GIT', 'GitHub', 'Jupyter notebook', 'Nginx'],
            'misc': ['Cloud.Yandex', 'Cloud.Reg', 'SCRUM', 'SOLID']
        }

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = WhoAmI()
    print(me)
```
