# Web--dev
git checkout -b Java 
echo 'public class AppRunner { public static void main(String[] args) { System.out.println("Java active"); } }' > AppRunner.java 
git add AppRunner.java 
git commit -m " Java setup done" 
git checkout main 
git checkout -b JavaScript 
echo 'console.log("JS script working");' > script.js 
git add script.js 
git commit -m " JS base ready " 
