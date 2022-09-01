# A couple projects for parsing packet data

1. packet_parser:
takes scrubbed data from .csv file and puts into a (soon to be) queryable class

2. speedguide:
command line tool for grabbing port info off speedguide <-- currently gets your ip blocked unless done through tor lol

`source bin/activate`
`apt install python3-bs4`
`pip3 install requests-tor`
`pip3 install html2text`

- install [tor](https://gist.github.com/DusanMadar/8d11026b7ce0bce6a67f7dd87b999f6b).
- setup ["Advanced usage"](https://pypi.org/project/requests-tor/) for `tor-request`

__NOTE:__
tor makes this shit nightmarishly slow, and it does occasionally bug out. 
looking more into this soon...
