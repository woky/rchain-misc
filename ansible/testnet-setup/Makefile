.ONESHELL:
bonds.txt: private/pyr10-private-keys.txt additional-public-keys.txt
	{
		../../validator-sk-to-pk <private/pyr10-private-keys.txt
		cat additional-public-keys.txt
	} | sed 's/$$/ 1000000/' >$@
