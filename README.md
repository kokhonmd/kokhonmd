public class UserProfile {
    private String username;
    private int age;
    private String email;

    // Constructor
    public UserProfile(String username, int age, String email) {
        this.username = username;
        this.age = age;
        this.email = email;
    }

    // Getters and Setters
    public String getUsername() {
        return username;
    }

    public void setUsername(String username) {
        this.username = username;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }

    public String getEmail() {
        return email;
    }

    public void setEmail(String email) {
        this.email = email;
    }

    // Display profile information
    public void displayProfile() {
        System.out.println("Username: " + username);
        System.out.println("Age: " + age);
        System.out.println("Email: " + email);
    }

    public static void main(String[] args) {
        // Create a user profile
        UserProfile userProfile = new UserProfile("john_doe", 25, "john@example.com");

        // Display profile information
        userProfile.displayProfile();
    }
}
