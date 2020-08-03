```py
class ywp:
    def __init__(self):
        self.variables = {
            'name': 'ywp',
            'hobby': 'coding', 'volleyball'
            'languages': ('English', 'Spanish')
        }

    def description(self):
        print('------ywp------')
        for index, value in enumerate(self.variables.values()):
            if index == 0:
                print(f'Name: {value}')
            elif index == 1:
                print(f'Hobby: {value}')
            elif index == 2:
                print(f'Languages: {value}')

    def medias(self):
        platforms = {
            'Discord': 'ywp#6969',
            'Github': 'ywppp',
            'Website': 'http://ywpp.tk'
        }

        print('\n-----contact-----')
        for key, value in platforms.items():
            print(f'{key}: {value}')


if __name__ == '__main__':
    ywpp = ywp()
    ywpp.description()
    ywpp.medias()
```
