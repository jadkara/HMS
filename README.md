https://teams.microsoft.com/l/meetup-join/19%3ameeting_YzM5YjE1ZDAtMzgyNy00MTA3LTliMDEtMjllMjY5ZTc0ODUw%40thread.v2/0?context=%7b%22Tid%22%3a%22363f8ad7-1be3-4f05-8a6b-4955756fe2f6%22%2c%22Oid%22%3a%2218f3f9f3-df2c-417a-9530-ef5da8f4a851%22%7d




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

	
	
