# Workshop-3-notes
Location
insert the request to access location on phone in "info.plist" in order to request permission.
- Privacy: Location Alway and Whn In Use
- Privacy: Location When In Use
You HAVE to do this.

in viewController:
      
      locationManager.requestAlways Authorization()
      location.startUpdatatingLoaction()
      locationManager.dlegate = self
      
      
(Outisde of viewController)

      extention ViewController: CLLocationManager Deleagte {
      
      }
      
      
[] = Array (a bit like a list)

[CLLocation] = An array of loactions


Limitation of emulator of is that it doesn't have GPS
- use the GPS simulator in the debug area (only there when you run the simulator)

  let currentLocation = locations.last!
  print (currentLocation)

