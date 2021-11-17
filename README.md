# Ferwaba-NPM
A js package that has all the ferwaba teams and players informations

install: npm install ferwaba


This package will allow anyone to pull the names of all the current palyers in the Rwandan Baskeball League and the teams

Function in the Package:

- getAllPlayers(): this function doesn't take any parameters. It will return a list of all the palyers with their respective informations
- getPlayerInfo(string parameter); This function takes in one parameter( the palyer's name, surname or middlename) and will return that player's informations.
    Eg: const ferwaba=require ('ferwaba');
        console.log(ferwaba.getPlayerInfo('RUTAZIGWA'));
        output:
        Player {
                  name: 'Cedric',
                  middlename: 'GITORI',
                  surname: 'RUTAZIGWA',
                  id: '#202',
                  fullname: 'RUTAZIGWA GITORI Cedric'
                }
                
-getAllTeams(): this function doesn't take any parameters. It will return a list of all the teams with their respective informations
-getTeamInfo(string parameter): This function takes in one parameter( the team's name) and will return that team's informations.
  Eg: const ferwaba=require ('ferwaba');
      console.log(ferwaba.getTeamInfo('APR BBC'));
      output:
      Team { name: 'APR BBC' }
      
      
      
      
      
      
