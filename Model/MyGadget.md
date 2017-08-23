##### Desctiption	
	- Wrapper of BLEGadget

##### Field
	- gadget : BLEGadget
    - dewPoint : Float
    - heatPoint : Float
    - temperature : Float
    - battery : Int (0-100)
    - humidity : Float
    - identify : String
    - downloadedData : ArrayList(MeasurementDataPoint)
    -  downloadProgress : Float
    - timer : Timer

    enum State {
         free
         downloading
    }


