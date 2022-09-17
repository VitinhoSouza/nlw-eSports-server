# Welcome to **nlw-eSports-server**👋
This is an API that has four endpoints related to games and game ads. Are they:
- **List Games** (*GET*): 'baseUrl/games';
- **List Ads By Game** (*GET*): 'baseUrl/games/:idGame/ads';
- **Get Discord By Ad** (*GET*): 'baseUrl/ads/:idAds/discord';
- **Create Ad** (*POST*): 'baseUrl/games/:idGame/ads', which expects an object 
  {name: (string), yearsPlaying(number), discord: (string), weekDays (array of number, where 0 is Sunday and 6 is Saturday), hourStart e hourEnd (string, ex: "18:00") and useVoiceChannel (boolean)}

## A preview of the application:
https://user-images.githubusercontent.com/51724518/190837954-4032025f-2b44-4a23-a552-49cd110b57fd.mp4


## Techs:
Built with **Express** + **Node**. Also used:
- **Prisma** to assist in the database part, generating tables faster;
- **TypeScript** to better define some application data.

## Get started:
- Open the terminal inside the project folder and do: *npm install*. When all packages are installed, do *npm run dev* to start in development mode.
