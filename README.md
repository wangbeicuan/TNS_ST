This is a transient notes.
fun:
    Get every day TNS information from TNS,then filter by dec and mag,(dec>-20,unit:deree,mag<18.8,unit:AB)
    next get 2 arcmin of TNS coordinates to get host redshift,choose no. 1 as redshift from top 10.
    then 'full_name', 'tns_ra_hms', 'tns_dec_hms','discoverymag','location','redshift','type','discoverydate','internal_names','host_name','host_ra_rms','host_dec_rms','ra','declination','filter','host_ra','host_dec','host_redshift','host_type','name_link'.
    v2. set center condition as 1.8 asc,add galaxy type,impove ST file object sort.
    v3.imporved redshift from top 10 data.
    v4.solved some debug:cut mag,repoted data,wider redshift range,solve - dec bug.