This is a transient notes.

fun:

    Get every day TNS information from TNS,then filter by dec and mag,(dec>-20,unit:deree,mag<=18.8,unit:AB)

    next get 2 arcmin of TNS coordinates from NED to get host redshift,choose no. 1 as redshift from top 10.

    'full_name,tns_ra_hms,tns_dec_hms,tns_ra,tns_dec,discoverydate,discovery_mag,filter,location,redshift,type,internal_names,host_name,host_ra_hms,host_dec_hms,host_ra,host_dec,host_redshift,host_type,TNS_link,ZTF_link' be saved.

    -->ref

    ATname,tns_ra_hms,tns_dec_hms,transient_ra,transient_dec,discoverydate,discoverymag,filter,location,redshift,type,internal_names,host_name,host_ra_hms,host_dec_hms,host_ra,host_dec,host_redshift,host_type,TNS_link,ZTF_link.
    {\textbf TNS_link,ZTF_link,you can copy,right to search links.}
update log:

    v2. set center condition as 1.8 asc,add galaxy type,impove ST file object sort.

    v3.imporved redshift from top 10 data.

    v4.solved some debug:cut mag,repoted data,wider redshift range,solve - dec bug.

dir:
    /TNS/TNS_ST/obs_csv:this is filtered transient every day.

    /TNS/TNS_ST/obs_plan:this is filtered transient obs plan every day.(now is wrong information,just ref)
