De-Id python project

###############Run deid-ChenLin.py######################

python3 deid-ChenLin.py id.text age.phi

python3 deid-ChenLin.py id.text PTname.phi

(Modify the "main" function of deid-ChenLin.py to deid_ptname(sys.argv[1], sys.argv[2]) )

python3 deid-ChenLin.py id.text HCPname.phi

(Modify the "main" function of deid-ChenLin.py to deid_hcpname(sys.argv[1], sys.argv[2]) )

python3 deid-ChenLin.py id.text Location.phi

(Modify the "main" function of deid-ChenLin.py to deid_location(sys.argv[1], sys.argv[2]) )

python3 deid-ChenLin.py id.text relativeName.phi

(Modify the "main" function of deid-ChenLin.py to deid_relativeName(sys.argv[1], sys.argv[2]) )

###############Run stats.py######################

python3 stats.py id.deid id-phi.phrase age.phi

python3 stats.py id.deid id-phi.phrase PTname.phi

python3 stats.py id.deid id-phi.phrase HCPname.phi

python3 stats.py id.deid id-phi.phrase Location.phi

python3 stats.py id.deid id-phi.phrase relativeName.phi




