### 🚆 Luas Timetable In Terminal

####Setup 🔌:
* Download [`JSON Helper`](https://itunes.apple.com/ie/app/json-helper-for-applescript/id453114608?mt=12)
* Checkout the luas [`API`](https://github.com/ncremins/luas-api) to set the `luasStop` variable to the station code

Variables | Instruction
--- | --- 
`set luasStop to "SAN"` | Find the code from the API to set the stop
`set stopName to "Sandyford"` | Add the name that you want to call the stop 
####Running 🏃:
To run the script you can cd into the directoy and run using 
`./luas home`
or 
`./luas work`

If you want to run it from anywhere you can move the executable to a location on your path. For example ⬇

* `mkdir .local/bin`
* Move `luas` file into the above folder
* Modify your bash profile and add the line : `export PATH=~/.local/bin:$PATH`

####Output 👀:
<img src="https://github.com/cifinn/luas-timetable-in-terminal/blob/master/images/image1.png" width="400" height="200" />
<img src="https://github.com/cifinn/luas-timetable-in-terminal/blob/master/images/image2.png" width="400" height="130" />
