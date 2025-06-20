# sohel-mehedi1619
# <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F64D3C&random=false&width=435&lines=Hello%2C+I'm+Mehedi+Hasan;Welcome+To+My+Profile" alt="Typing SVG" /></a>


<img src="https://raw.githubusercontent.com/AkashRajpurohit/AkashRajpurohit/master/assets/github-snake-dark.svg" />

public class Point {
    private int x;
    private int y;
    public Point(int x, int y) { 
        this.x = x; 
        this.y = y; 
    }
	
    @Override
    public boolean equals(Object that) {
        // Kompaktere Schreibweise.
        return that instanceof Point && ((Point)that).x == x && ((Point)that).y == y;
    }
}
