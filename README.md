# Call of Juarez 2 Dedicated Server Utils
Generate a DedicatedServerSettings.ini for CoJ2

Custom Maps can be found [here](https://github.com/ddoylez/coj2_maps).
### Options

  -h, --help            show this help message and exit
  
  -i {0,1}, --internet-server {0,1}
                        LAN = 0, Internet = 1, 0 by default
  
  -ps PUBLIC_SLOTS, --public-slots PUBLIC_SLOTS
                        number of public slots (max players), 12 by default
  
  -p2s PLAYERS_TO_START, --players-to-start PLAYERS_TO_START
                        minimum number of players for the game to begin, 1 by
                        default
  
  -dp POINTS_LIMIT_DEFAULT, --points-limit-default POINTS_LIMIT_DEFAULT
                        target number of points for the game to end for
                        teamwanted
  
  -db BOUNTY_LIMIT_DEFAULT, --bounty-limit-default BOUNTY_LIMIT_DEFAULT
                        target of bounty for the game to end for applicable
                        modes
  
  -dt TIME_LIMIT_DEFAULT, --time-limit-default TIME_LIMIT_DEFAULT
                        map time limit in seconds for applicable modes
  
  -dmb BOUNTY_LIMIT_DEATHMATCH, --bounty-limit-deathmatch BOUNTY_LIMIT_DEATHMATCH
                        target of bounty for the game to end for deathmatch
  
  -dmt TIME_LIMIT_DEATHMATCH, --time-limit-deathmatch TIME_LIMIT_DEATHMATCH
                        map time limit in seconds in for deathmatch
  
  -tdmb BOUNTY_LIMIT_TEAMDEATHMATCH, --bounty-limit-teamdeathmatch BOUNTY_LIMIT_TEAMDEATHMATCH
                        target of bounty for the game to end for
                        teamdeathmatch
  
  -tdmt TIME_LIMIT_TEAMDEATHMATCH, --time-limit-teamdeathmatch TIME_LIMIT_TEAMDEATHMATCH
                        map time limit in seconds in for teamdeathmatch
  
  -wb BOUNTY_LIMIT_WANTED, --bounty-limit-wanted BOUNTY_LIMIT_WANTED
                        target of bounty for the game to end for wanted
  
  -wt TIME_LIMIT_WANTED, --time-limit-wanted TIME_LIMIT_WANTED
                        map time limit in seconds in for wanted
  
  -twp POINTS_LIMIT_TEAMWANTED, --points-limit-teamwanted POINTS_LIMIT_TEAMWANTED
                        target number of points for the game to end in
                        teamwanted
  
  -twt TIME_LIMIT_TEAMWANTED, --time-limit-teamwanted TIME_LIMIT_TEAMWANTED
                        map time limit in seconds in for teamwanted
  
  -ff {0,1}, --friendly-fire {0,1}
                        Off = 0, On = 1, 1 by default
  
  -name SERVER_NAME, --server-name SERVER_NAME
                        server name visible on the server list
  
  -pass SERVER_PASSWORD, --server-password SERVER_PASSWORD
                        password for starting the server
  
  -port SERVER_PORT, --server-port SERVER_PORT
                        port the server is running on, 27632 by default
  
  -m {historical,deathmatch,teamdeathmatch,wanted,teamwanted}, --mode {historical,deathmatch,teamdeathmatch,wanted,teamwanted}
                        can specify multiple times, deathmatch by default
  
  -l MAP_LIMIT, --map-limit MAP_LIMIT
                        limit how many "Map" entries are made, unlimited by
                        default
  
  -c, --custom-maps, --no-custom-maps
                        adds custom maps into selection pool (default: False)
  
  -o OUTPUT_FILE, --output-file OUTPUT_FILE
                        file to write settings to
  
  -s SEED, --seed SEED  seed for map shuffle
  
  -v, --version         show program's version number and exit
