package model;

public class Akun {
    private String username;
    private String NIM;
    private String email;
    private String kelas;

    public Akun setUsername(String username) {
        this.username = username;
        return this;
    }
    public String getUsername() {
        return this.username;
    }

    public Akun setNIM(String NIM) {
        this.NIM = NIM;
        return this;
    }
    public String getNIM() {
        return this.NIM;
    }
    
    public Akun setEmail(String email) {
        this.email = email;
        return this;
    }
    public String getEmail() {
        return this.email;
    }

    public Akun setKelas(String kelas) {
        this.kelas = kelas;
        return this;
    }
    public String getKelas() {
        return this.kelas;
    }
}
