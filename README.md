# Repro Steps
- `cd ./appshell` and run `npm i` and then `npm run build`
- `cd ../BlazorPilet` and run `dotnet build`
- `cd ../piral~/BlazorPilet` and run `pilet debug`

#  Problem
Open `http://localhost:1234/counter` in the latest Version of Google Chrome.
the Browsers console shows the following errors:
![alt text](image.png)