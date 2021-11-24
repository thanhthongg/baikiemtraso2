using System;
using System.Collections.Generic;
using System.Text;

namespace BaiKT
{
    class NVien
    {
        protected string maso;
        protected string hoten;
        protected string phai;
        protected string ngaysinh;
    }
    class NhanV : NVien
    {
        private string bangcap;
        public string Maso { get => maso; set => maso = value; }
        public string Hoten { get => hoten; set => hoten = value; }
        public string Phai { get => phai; set => phai = value; }
        public string Ngaysinh { get => ngaysinh; set => ngaysinh = value; }
        public string Bangcap { get => bangcap; set => bangcap = value; }
        public NhanV(string MS, string HT, string PP, string NS, string BC)
        {
            Maso = MS;
            Hoten = HT;
            Phai = PP;
            Ngaysinh = NS;
            Bangcap = BC;
        }
        public void infor()
        {
            Console.WriteLine("\n");
            Console.WriteLine("MaNV: {0}", Maso);
            Console.WriteLine("HoTen: {0}", Hoten);
            Console.WriteLine("GioiTinh: {0}", Phai);
            Console.WriteLine("NgaySinh: {0}", Ngaysinh);
            Console.WriteLine("BangCap: {0}\n", Bangcap);
        }
    }
    class Khachhang : NVien
    {
        private string loaiKH;
        public string Maso { get => maso; set => maso = value; }
        public string Hoten { get => hoten; set => hoten = value; }
        public string Phai { get => phai; set => phai = value; }
        public string Ngaysinh { get => ngaysinh; set => ngaysinh = value; }
        public string LoaiKH { get => loaiKH; set => loaiKH = value; }
        public Khachhang(string MS, string HT, string PP, string NS, string KH)
        {
            Maso = MS;
            Hoten = HT;
            Phai = PP;
            Ngaysinh = NS;
            LoaiKH = KH;
        }
        public void infor()
        {
            Console.WriteLine("\n");
            Console.WriteLine("MaKH: {0}", Maso);
            Console.WriteLine("HoTen: {0}", Hoten);
            Console.WriteLine("GioiTinh: {0}", Phai);
            Console.WriteLine("NgaySinh: {0}", Ngaysinh);
            Console.WriteLine("LoaiKH: {0}\n", LoaiKH);
        }
    }
}
