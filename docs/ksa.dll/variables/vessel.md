# Vessels
## Disclaimer
More variables are needed, as not all variables are in here yet, just the important ones
## Misc
- bool: Vehicle._showOrbit
- double: Vehicle.AudibleDistance
- AstonomicalTemplate: Vehicle.BodyTemplate
- List: Vehicle.ChildList
## Body/Vessel Variables Related to Movement
- double3: Vehicle.Orbit.AccelerationBody
- double: Vehicle.KinematicMeasurements.AngularAccelerationBody
- double: Vehicle.Orbit.Apoapsis
- double: Vehicle.Orbit.Eccentricity
- double: Vehicle.Orbit.Inclination
- double: Vehicle.Orbit.LongitudeOfAscendingNode
- Orbit: Vehicle.Orbit.Orbit
- KinematicMeasurements: Vehicle.KinematicMeasurements
- double: Vehicle.LastKinematicStates.PropellantMass
- double: Vehicle.Orbit.SemiMajorAxis
- double: Vehicle.Orbit.SemiMinorAxis
- bool: Vehicle.Program.ControlledVehicle?.Target
- double: Vehicle.Orbit.Period
## Body/Vessel Specs
- bool: Vehicle.IsTarget
- string: Vehicle.Class
- FlightPlan: Vehicle.FlightPlan
- BurnPlan: Vehicle.BurnPlan
- double: Vehicle.BoundingSphereRadius
- NavBallData (readonly): Vehicle._navBallData
## Time
- SimTime: Vehicle.NextApoapsisTime
- SimTime: Vehicle.NextPeriapsisTime
- SimTime: Vehicle.Orbit.GetElapsedTimeSincePeriapsis
- SimTime: Vehicle.Orbit.TimeAtPeriapsis