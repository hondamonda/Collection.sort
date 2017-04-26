# Collection.sort

  Collections.sort(persons, (firstPerson, secondPerson) -> {
	        int sComp = firstPerson.getFirstName().compareTo(secondPerson.getFirstName());

	        if (sComp != 0) {
	            return sComp;
	        } else {
	            return firstPerson.getAge().compareTo(secondPerson.getAge());
              // compareTo <=> - 
	        }
	    });
