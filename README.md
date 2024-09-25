# GAMMA-SKS-Caliber-Conversion

A simple change in the configs so the SKS family has the correct damage when converted to 7.62x54R. I took the liberty to change a couple of things:

1. SKS Molot RPM is 350 (prev 270). Always thought that this gun should be a direct upgrade to grandpa's ol'reliable default SKS, yet for some reason it has 270 RPM.

2. Caliber conversion upgrade changes following rapameters of a gun:
  + 2.1 RPM is lowered by 200, mainly because the SKS Tactical has a 600 RPM, so the upgraded version won't go toe-to-toe with the SVDS.
  + 2.2 Damage of the gun (hit_power) is increased from 0.58 to 1.1 (this is the main reason why SKS damage sucks after the conversion)
  + 2.3 Upgrade cost is 20640 roubles now (x3 the default one)
  + 2.4 Other minor gun parameters have been adjusted so that it is on par with other 7.62R rifles:
      * fire_distance +100 meters
      * bullet_speed +120 m/s
      * hit_impulse is increased to 40
