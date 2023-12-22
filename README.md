# bluepill_target

## usage
    
    # Make venv, don't fuck up your main env.
 
    python3 -m venv venv
    source venv/bin/activate

    # Install platformio
    
    python3 -m pip install -U platformio

## set upload_protocol in platform.ini

    upload_protocol = < jlink, stlink, etc... >

## Load onto device

    platformio run -t upload
