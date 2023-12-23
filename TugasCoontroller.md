package controller;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;
import java.util.Scanner;

import model.Mahasiswa;
import model.Akun;
import model.MataKuliah;
import model.Tugas;

public class TugasController {
    HashMap<String, MataKuliah> mataKuliahs = new HashMap();
    ArrayList<Tugas> tugass = new ArrayList<>();
    ArrayList<Akun> daftarMahasiswa = new ArrayList<>();
    ArrayList<Tugas> tugas = new ArrayList<>();
    int noIdMahasiswa = 0;
    int noTugas = 0;

    public void setUp() {
        MataKuliah mataKuliah1 = new MataKuliah();
        MataKuliah mataKuliah2 = new MataKuliah();
        MataKuliah mataKuliah3 = new MataKuliah();
        MataKuliah mataKuliah4 = new MataKuliah();
        MataKuliah mataKuliah5 = new MataKuliah();
        MataKuliah mataKuliah6 = new MataKuliah();
        MataKuliah mataKuliah7 = new MataKuliah();
        MataKuliah mataKuliah8 = new MataKuliah();
        MataKuliah mataKuliah9 = new MataKuliah();
        MataKuliah mataKuliah10 = new MataKuliah();
        MataKuliah mataKuliah11 = new MataKuliah();
        mataKuliah1.setIdMatkul("01").setHariMatkul("Senin").setNamaMatkul("Dasar Pemrograman").setDosenMatkul("Ichsan Budiman MT").setJamMatkul("12.40").setRuanganMatkul("4.10");
        mataKuliah2.setIdMatkul("02").setHariMatkul("Senin").setNamaMatkul("Kewarganegaraan").setDosenMatkul("Dr. H. Buhori M. M.Ag").setJamMatkul("14.20").setRuanganMatkul("4.12");
        mataKuliah3.setIdMatkul("03").setHariMatkul("Selasa").setNamaMatkul("Fisika Dasar").setDosenMatkul("Khoerun Nisa Syajaah M.Si").setJamMatkul("07.00").setRuanganMatkul("4.11");
        mataKuliah4.setIdMatkul("04").setHariMatkul("Selasa").setNamaMatkul("Kalkulus I").setDosenMatkul("Dr. Esih Sukaesih").setJamMatkul("9.30").setRuanganMatkul("4.01");
        mataKuliah5.setIdMatkul("05").setHariMatkul("Selasa").setNamaMatkul("Bahasa Arab").setDosenMatkul("Dede Sutisna M.Pd.I").setJamMatkul("14.20").setRuanganMatkul("4.11");
        mataKuliah6.setIdMatkul("06").setHariMatkul("Rabu").setNamaMatkul("Ilmu Fiqih").setDosenMatkul("Dr. Mohammad Jaenudin M.Ag., M.Pd").setJamMatkul("07.00").setRuanganMatkul("4.11");
        mataKuliah7.setIdMatkul("07").setHariMatkul("Rabu").setNamaMatkul("Pengenalan Informatika").setDosenMatkul("Muhammad Insan Al Amin MT").setJamMatkul("10.20").setRuanganMatkul("4.10");
        mataKuliah8.setIdMatkul("08").setHariMatkul("Kamis").setNamaMatkul("Praktikum Fisika Dasar").setDosenMatkul("Abdi Wadud Syafii, S.Si., M.Si").setJamMatkul("08.00").setRuanganMatkul("Lab");
        mataKuliah9.setIdMatkul("09").setHariMatkul("Kamis").setNamaMatkul("Praktikum Dasar Pemrograman").setDosenMatkul("Popon Dauni ST.M.Kom").setJamMatkul("10.20").setRuanganMatkul("Lab");
        mataKuliah10.setIdMatkul("10").setHariMatkul("Kamis").setNamaMatkul("Olahraga").setDosenMatkul("Alvin Yanuar Rahman M.Or").setJamMatkul("14.30").setRuanganMatkul("Kampus 2");
        mataKuliah11.setIdMatkul("11").setHariMatkul("Jumat").setNamaMatkul("Bahasa Inggris").setDosenMatkul("Nopianti Sa'adah S.Pd., M.Pd").setJamMatkul("12.40").setRuanganMatkul("4.10");
        
        mataKuliahs.put(mataKuliah1.getIdMatkul(), mataKuliah1);
        mataKuliahs.put(mataKuliah2.getIdMatkul(), mataKuliah2);
        mataKuliahs.put(mataKuliah3.getIdMatkul(), mataKuliah3);
        mataKuliahs.put(mataKuliah4.getIdMatkul(), mataKuliah4);
        mataKuliahs.put(mataKuliah5.getIdMatkul(), mataKuliah5);
        mataKuliahs.put(mataKuliah6.getIdMatkul(), mataKuliah6);
        mataKuliahs.put(mataKuliah7.getIdMatkul(), mataKuliah7);
        mataKuliahs.put(mataKuliah8.getIdMatkul(), mataKuliah8);
        mataKuliahs.put(mataKuliah9.getIdMatkul(), mataKuliah9);
        mataKuliahs.put(mataKuliah10.getIdMatkul(), mataKuliah10);
        mataKuliahs.put(mataKuliah11.getIdMatkul(), mataKuliah11);
    }
