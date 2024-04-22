String input = "SILENT";

	String sinput = "LISTENK";

	char[] inputarr = input.toCharArray();

	int count = 0;
	
	for(int i = 0; i< inputarr.length ;i++){

		boolean confirma = false;
		for (int j = 0; j < input.length(); j++) {

			if (sinput.charAt(i) == inputarr[j]) {
				confirma = true;
				break;

			}
		}
		if(confirma == true) {
			count++;
		}else {
			count--;
		}
	}
	if(input.length()==count) {
		System.out.println("anangram");
	}
	else {
		System.out.println("not anngram");
	}
