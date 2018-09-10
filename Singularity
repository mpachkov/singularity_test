Bootstrap: shub
From: singularityhub/ubuntu

%runscript
    exec echo "The runscript is the containers default runtime command!" && cat /opt/text.txt

%files
   
%environment
    VARIABLE=MEATBALLVALUE
    export VARIABLE

%labels
   AUTHOR mike

%post
    echo 'Mike: MyTest!!! '
    echo 'Mike: I am done!'
