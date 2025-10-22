# metasploit-labkit-mj
The toolkit contains installation scripts, a runner, and Docker configuration for safely running the Metasploit Framework in your own lab environment. Does not include exploits/payloads. For authorized learning and testing purposes only.

# Metasploit Toolkit — MJ

**Deskripsi singkat**  
Toolkit ini menyediakan helper scripts, Docker workflows, dan petunjuk cepat untuk men-setup dan menjalankan **Metasploit Framework** di lab pribadi. Repo ini **tidak** menyertakan modul eksploit atau payload apa pun — hanya alat instalasi, runner, dan dokumentasi untuk penggunaan edukatif dan pengujian berizin.

## Isi repo
- `install_msf.sh` — skrip clone + install dependencies (Ubuntu/Debian)
- `run_msfconsole.sh` — wrapper untuk menjalankan msfconsole
- `docker-compose.yml` — contoh untuk menjalankan Metasploit ter-isolasi via Docker
- `README.md` — dokumentasi & pedoman etis
- `LICENSE` — MIT (atau lisensi pilihan MJ)

## Rules & Etika
Gunakan toolkit ini hanya untuk:
- Lab pribadi milikmu
- Pengujian yang sudah mendapat izin tertulis
- Pembelajaran dan riset keamanan secara etis

Dilarang: menggunakan toolkit ini untuk menyerang sistem tanpa izin — tindakan tersebut melanggar hukum.

## Cara cepat
```bash
git clone https://github.com/YOUR_USERNAME/metasploit-toolkit.git
cd metasploit-toolkit
chmod +x install_msf.sh run_msfconsole.sh
sudo ./install_msf.sh
./run_msfconsole.sh
