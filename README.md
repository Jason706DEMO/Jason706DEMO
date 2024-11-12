public class Person {
    private String name;
    private int age;
    private String profession;
    private String hobby;

    public Person(String name, int age, String profession, String hobby) {
        this.name = name;
        this.age = age;
        this.profession = profession;
        this.hobby = hobby;
    }

    public void introduce() {
        System.out.println("大家好，我叫 " + name + "。");
        System.out.println("我今年 " + age + " 岁。");
        System.out.println("我的职业是 " + profession + "。");
        System.out.println("我的兴趣爱好是 " + hobby + "。");
        System.out.println("很高兴认识大家！");
    }

    public static void main(String[] args) {
        // 创建一个Person对象，并输出自我介绍
        Person person = new Person("Jason", 25, "软件工程师", "阅读和旅行");
        person.introduce();
    }
}
