---
date: 2017-12-11 14:46:24
description: 'Model simulations

  The main model simulations conducted by PRIMAVERA groups follow the CMIP6 HighResMIP
  protocol. The model outputs are currently being made available on the CMIP ESGF
  (Earth System Grid Federation).'
layout: base_primavera
order: 3
permalink: /modelling/data-code/
title: Data access & code
---

<h3>Model simulations</h3>
<p>The main model simulations conducted by PRIMAVERA groups follow the CMIP6 HighResMIP protocol. The model outputs are currently being made available on the <a href="https://esgf-index1.ceda.ac.uk/search/cmip6-ceda/" title="ESGF CMIP6 index">CMIP ESGF</a> (Earth System Grid Federation).</p>
<p>The project itself has all these simulations available on the <a href="https://www.ceda.ac.uk/services/jasmin/">CEDA-JASMIN</a> platform, mainly on tape. We use the <strong>PRIMAVERA DMT</strong> (Data Management Tool) to select and extract the data from tape to disk. This tool can also be used to query which CMOR-formatted variables are available from our simulations. The DMT is available for users to query the available data. <a class="ext-link" href="https://docs.google.com/document/d/1rz4KB3xFUiqsWsCd85Kv4HIBOPM5e7n8QHa6urxWdXY">​View the DMT user guide</a></p>
<p>To avoid having to read all of the user guide, please go to <a class="ext-link" href="https://prima-dm1.jasmin.ac.uk/received_data_quick_query/">https://prima-dm1.jasmin.ac.uk/received_data_quick_query/</a> to see what data has been received. Hopefully the search is fairly intuitive. If not, then please let us know and we will work to improve it, or to improve its documentation.</p>
<p><em>If you would like to collaborate with PRIMAVERA and use CEDA-JASMIN with us to conduct complementary analysis, then please contact us for details. A summary of the required technical steps is available below.</em></p>
<p>Further information on coordinated analysis of the HighResMIP simulations <a href="https://www.primavera-h2020.eu/output/outreach-and-collaboration/">is available</a>.</p>
<h3>Data access for CLIVAR and other groups</h3>
<p>Users of PRIMAVERA data (e.g. CLIVAR collaborators and others) should follow the instructions at <a href="http://help.jasmin.ac.uk/article/189-get-started-with-jasmin" title="JASMIN Getting Started Guide">http://help.jasmin.ac.uk/article/189-get-started-with-jasmin</a> to get access to the <strong>JASMIN</strong> facilities:</p>
<ul>
<li>At step 4, applying for the jasmin-login role, you should include the email addresses of two UK-based PRIMAVERA project member who can provide you with a reference to support your application. Hence you will need to speak with us before you apply.</li>
<li>To access the data you will need to register for a CEDA account at&nbsp;<a class="ext-link" href="http://www.ceda.ac.uk/">​http://www.ceda.ac.uk/</a>&nbsp;and link this to your JASMIN account at&nbsp;<a class="ext-link" href="https://accounts.jasmin.ac.uk/account/profile/">​https://accounts.jasmin.ac.uk/account/profile/</a> to get access to the CEDA archives.</li>
</ul>
<!--<p>There are some short videos to get you used to working with JASMIN at <a href="https://light.ceda.ac.uk/primavera/jasmin_docs/" title="JASMIN Training Videos">https://light.ceda.ac.uk/primavera/jasmin_docs/</a></p>-->
<p>The data that is available can be queried using the <strong>DMT</strong> (Data Management Tool) available at <a href="https://prima-dm1.jasmin.ac.uk/" title="PRIMAVERA Data Management Tool">https://prima-dm1.jasmin.ac.uk/</a>. Most people will find the Variables Received Query (<a href="https://prima-dm1.jasmin.ac.uk/received_data_quick_query/" title="DMT Variables Received Query">https://prima-dm1.jasmin.ac.uk/received_data_quick_query/</a>) is the best way to search through the available data. Data will have an &ldquo;Online Status&rdquo; of online if all of that data is currently available on disk, and offline or partial if some data is only available on tape. If data is only available on tape then users can use the request retrieval buttons to the right of the table and the &ldquo;Create Retrieval Request&rdquo; button at the bottom of the page to request that data is restored from tape to disk. Restoring data from tape to disk may take several days depending upon how busy the tape system is.&nbsp;&nbsp;</p>
<p>Anyone can use the DMT&rsquo;s queries to search for available data. The complete user guide for the DMT is available from <a href="https://docs.google.com/document/d/1rz4KB3xFUiqsWsCd85Kv4HIBOPM5e7n8QHa6urxWdXY/" title="DMT User's Guide">https://docs.google.com/document/d/1rz4KB3xFUiqsWsCd85Kv4HIBOPM5e7n8QHa6urxWdXY/</a></p>
<p>The PRIMAVERA group workspaces at JASMIN are no longer available and their storage has been handed back for use by other projects. All of the data produced is available from the CEDA archives instead and can be accessed by following the instructions above for CEDA archive access. The paths in the DMT show the path to the data in the CEDA archives. Users wishing to store intermediate files should use <a href="https://help.jasmin.ac.uk/article/176-storage#disktemp">JASMIN temporary storage</a>.</p>
<h3>Code resources</h3>
<p>We are building up a library of useful utilities within the project which may have a wider application. Please see the github site:&nbsp;<a href="https://github.com/PRIMAVERA-H2020">https://github.com/PRIMAVERA-H2020</a></p>
<p>We have a variety of packages of code, including:</p>
<ul>
<li><strong>HighResMIP-storm_reader</strong>: Python code to read the CMOR-like storm files that will become available on the CEDA archives</li>
<li><strong>HighResMIP-extreme_indices</strong>:&nbsp;Python code using the <a href="https://icclim.readthedocs.io/en/latest/">ICCLIM package</a> to calculate climate extreme indices</li>
<li><strong>HighResMIP-futureSSTSeaice</strong>: code base used to generate the future SST and sea-ice forcing for the HighResMIP experiment highresSST-future out to 2050</li>
</ul>
<p>Coming soon: standard code used to calculate other model indices (such as AMO, AMM, El Nino), as well as code to calculate power spectra and the like, to be used in forthcoming manuscripts from the project.</p>
<h3>Data resources</h3>
<p>Full data outputs from the models (as per the CMIP6 HighResMIP data request specification) are now being published on <a href="https://esgf-index1.ceda.ac.uk/search/cmip6-ceda/" title="ESGF CMIP6 index">the ESGF</a>.</p>
<p></p>
<h4>Tropical and extra-tropical cyclones</h4>
<p>Tracking the model simulations (using TRACK and TempestExtremes algorithms to far) for both tropical and extra-tropical storms in ongoing. This data is available at CEDA-JASMIN and from the CEDA archives at <a href="https://catalogue.ceda.ac.uk/uuid/e82a62d926d7448696a2b60c1925f811">https://catalogue.ceda.ac.uk/uuid/e82a62d926d7448696a2b60c1925f811</a>.</p>
<p>The list of models that have been tracked can be seen at this <a href="https://docs.google.com/document/d/14DZBdZRpZ5P2wIEtl8se6SRtDVZ61FairXVBDKKhipQ/edit">Google doc</a>.</p>
<p></p>
<h4>Climate extremes indices</h4>
<p>These are being calculated using the ICCLIM software (see above). Michael Wehner has made these available via a server at Berkeley: <a href="http://portal.nersc.gov/archive/home/projects/cascade/www/ETCCDI/" title="ICCLIM software">http://portal.nersc.gov/archive/home/projects/cascade/www/ETCCDI/</a></p>
<h3>Tutorial - Accessing the data from the ESGF</h3>
<p>The Earh System Grid Federation (ESGF) was developed to disseminate data from all <a href="https://www.wcrp-climate.org/wgcm-cmip/" rel="noopener" target="_blank" title="WGCM CMIP homepage">CMIP</a> models and experiments and so can be confusing for first time users. This is brief tutorial to help you get started.</p>
<p>The ESGF is a distributed grid of data nodes. There are many nodes around the world. You can use any node to browse through the metadata published to any of the other nodes. When you download a file your download will automatically be redirected to the node that holds the file.</p>
<p>All PRIMAVERA data was published to the HighResMIP activity and is available from the&nbsp;<a href="https://esgf-index1.ceda.ac.uk/search/primavera-ceda/" title="PRIMAVERA data on CEDA's ESGF node">PRIMAVERA data search on CEDA's ESGF node</a>. Many other institutes have also contributed data to HighResMIP and so you will also see non-PRIMAVERA data in the ESGF search. You can see the names of the PRIMAVERA models on <a href="{{ site.baseurl }}/modelling/" title="Modelling">our Modelling page</a>.</p>
<p>Once you have chosen the HighResMIP activity then setting the "Experiment" is a useful way to further subset the data. You can find details of the PRIMAVERA experiments on <a href="{{ site.baseurl }}/modelling/our-simulations/" title="Modelling / Our Simulations">Our Simulations page</a>. To chose individual variables then you can use the "Variable" or "CF Standard Name" searches on the left-hand side of the ESGF search page. The "Variable" names may not be intuitive at first. The "CF Standard Name" is probably more intuitive. The CF Standard names are defined on <a href="http://cfconventions.org/standard-names.html" title="CF Conventions">CF Conventions website</a>. An example variable is "tas" which has a CF Standard Name of "air_temperature".</p>
<p>A typical dataset on the ESGF search looks like:</p>
<p><img alt="ESGF entry for a typical dataset" height="100" src="{{ site.baseurl }}/assets/media/uploads/esgf_dataset_entry.png" title="ESGF entry for a typical dataset" width="923"></p>
<p>The "THREDDS Catalog" link will allow you to download individual files and requires no registration or account. However, some datasets can be split over many files and so this could be time consuming.</p>
<p>The "WGET Script" link will download a BASH script that when run with the -H option will download the chosen dataset. BASH scripts can be run natively on Mac, Linux and Unix operating systems. Various BASH shells can be installed for Windows. You will also need the wget software installed,&nbsp; which comes with many operating systems but is available for all. To use the WGET Script you will need to register for a free CEDA account at <a href="http://archive.ceda.ac.uk/">http://archive.ceda.ac.uk/</a>. When running the WGET script you will be prompted to enter your CEDA OpenID and CEDA password.</p>
