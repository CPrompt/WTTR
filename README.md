# WTTR
Module for i3pystatus to pull weather information from wttr.in

This modules uses the "wttr.in" site to pull the current weather (high and low temps)
as well as displays icons corresponding to the weather.

More usage on wttr can be found from the github repo: https://github.com/chubin/wttr.in

To find your location to use in the config file, simply navigate to wttr.in and 
in the top right corner you will see "Weather report:" and your location.  Simply copy paste that
information in your config for i3pystatus.

i.e.


status.register("wttr",
                location="High Point, North Carolina",
                units="F",
                )

