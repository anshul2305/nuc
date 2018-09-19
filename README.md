# nuc
uytuytyut
package pkg;

import java.util.Scanner;

public class BookStore {
	public static void main(String[] args) {
		
		Scanner sc=new Scanner(System.in);
		System.out.println("book store");
		System.out.println();
		System.out.println("1. title of book");
		System.out.println("2. order new book ");
		System.out.println("3. sell book");
		System.out.println("4. exit ");
	}
	public void display(){
		Books []books=new Books[10];
		for(int i=0;i<10;i++){
			if(books[i].getBooktitle()+""+books[i].getAuthor()+""+books[i].getIsbn()+""+books[i].getNumofcopies);
		}
		
	}

}


























package pkg;

public class Books {
	private String booktitle;
	private String author;
	private String isbn;
	private int numofcopies;

      public Books(String booktitle,String author,String isbn,int numofcopies){
    	  this.booktitle=booktitle;
    	  this.author=author;
    	  this.isbn=isbn;
    	  this.numofcopies=numofcopies;
    	  
}

	public String getBooktitle() {
		return booktitle;
	}

	public void setBooktitle(String booktitle) {
		this.booktitle = booktitle;
	}

	public String getAuthor() {
		return author;
	}

	public void setAuthor(String author) {
		this.author = author;
	}

	public String getIsbn() {
		return isbn;
	}

	public void setIsbn(String isbn) {
		this.isbn = isbn;
	}

	public int getNumofcopies() {
		return numofcopies;
	}

	public void setNumofcopies(int numofcopies) {
		this.numofcopies = numofcopies;
	}
      }
