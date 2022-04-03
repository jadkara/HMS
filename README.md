Photon
https://teams.microsoft.com/l/meetup-join/19%3ameeting_YTQ1MTY1MjAtYTRiZS00M2I3LThmZmUtYTE0ODhmODhhMjI1%40thread.v2/0?context=%7b%22Tid%22%3a%221a30f1d1-eb8c-40cc-8741-f31eee8fc067%22%2c%22Oid%22%3a%22352d1966-1ee8-42ac-a8b0-dd1f4303b616%22%7d


Infy
https://www.google.com/url?q=https%3A%2F%2Fus02web.zoom.us%2Fj%2F4474760240&sa=D&source=calendar&usd=2&usg=AOvVaw1gJ7hoHfYzE3uLOQ8yNdwD


Xebia
https://teams.microsoft.com/l/meetup-join/19%3ameeting_Mjg5ODE0NjQtZjdjMC00NGQ0LWI2NTQtZTI0ZmRlNTdkNzY4%40thread.v2/0?context=%7b%22Tid%22%3a%223d4d17ea-1ae4-4705-947e-51369c5a5f79%22%2c%22Oid%22%3a%22e7251139-4d83-49b1-aaa8-1620f61e0e11%22%7d


Tiaa

https://tiaa.zoom.us/j/9696999867?pwd=RWFqbmtPMit0RktsSXpCZE1Fd3VmZz09







http://sgsub.notify.evalground.com/ls/click?upn=QmR1XE97ru3Re9-2BtL6rDxgzzYJJJp8-2BdTwYygU9x05SrqpKaEn1VVhbUxqTDrJImTx4KSBIIKGSwaC913Pv0nHwn7QTJn-2B-2FYRz3qAFv4Eo7O5L-2FIAGS3t3g21OZQTYpD651Y6a6-2FHUJRhOLItvVvXl4mLiEzoYrwUE0tWsdcgMI-2Bsfc871SFSf6dndSFxI81eCtViVI2BWIeBM4Iwot9JteiJbU-2BGBxHMZwfmw78jFM-3DlX2j_x6gmTz73ZHM-2F6OdR0sAoX7YeckcKW5sJ02TphPeHapArZg9ThSElxfJnNRYenLm-2FrK-2FBm8WVx3bRsAGm-2B6UsC1UUi-2BSZ2Vmog9EY9jx-2Bj-2BffQ-2BrEqLCheXkxqSYneuzji9Q6IIttBXllEguIvDfCOADBO9zlw6iGq3jiBYCUvTXfaQaUSNYfv244On6rJ5HpdSCoANR4drOJbTVki-2FEhkiZFqT7Fvf0-2FW8eYbOkXJ4M-3D

Example : Array : 2,5,6,7,8,8,9 

Target number : 5 Output : 5

Target number : 11 Output : 9

int target = 5;
int closeValue =0;
int closeValueDifference =0;
for(int value:arr) {
	//negative condiiition
	
	if(value = target) {
		closeValue = value;
		break;
	}
	else {
		int processValue = 0;
		if(value < 0) {
			if(value > target)
		  		processValue = target - value;
		else
				processValue = value - target;
		} else {
			if(value > target)
		  		processValue = value - target;
			else
				processValue = target - value;
		}
		if(closeValueDifference > processValue)
			closeValue = value;
	}
}
System.out.println(closeValue);

	
	
