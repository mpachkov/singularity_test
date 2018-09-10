Bootstrap: shub
From: singularityhub/ubuntu

%runscript
    exec echo "The runscript is the containers default runtime command!" && cat /opt/text.txt

%files
   /scicore/home/nimwegen/pachko/singularity/test1/test.txt    /opt/
%environment
    VARIABLE=MEATBALLVALUE
    export VARIABLE

%labels
   AUTHOR mike

%post
    echo "Mike: I am done!"
