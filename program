using System;
using System.Collections.Generic;

namespace BaiKT
{
    class Program
    {
        static void Main(string[] args)
        {
            List<NhanV> DSDV = new List<NhanV>();
            List<Khachhang> DBDV = new List<Khachhang>();
            while (true)
            {
                Menu();
                Console.WriteLine("\n");
                Console.WriteLine("lua chon:");
                string TD = Console.ReadLine();
                if (TD == "ae")
                {
                    ThemNhanvien(DSDV);
                }
                else if (TD == "ac")
                {
                    Themkhachhang(DBDV);
                }
                else if (TD == "dae")
                {
                    TTNV(DSDV);
                }
                else if (TD == "dac")
                {
                    TTKH(DBDV);
                }
                else if (TD == "cs")
                {
                    TKKH(DBDV);
                }
            }
        }
        static void ThemNhanvien(List<NhanV> DSDV)
        {
            Console.Write("TenNV:");
            string NV1 = Console.ReadLine();
            Console.Write("MaNV:");
            string NV2 = Console.ReadLine();
            Console.Write("GioiTinh:");
            string NV3 = Console.ReadLine();
            Console.Write("NgaySinh:");
            string NV4 = Console.ReadLine();
            Console.Write("BangCap:");
            string NV5 = Console.ReadLine();
            Console.WriteLine("\n");
            NhanV NV = new NhanV(NV1, NV2, NV3, NV4, NV5);
            DSDV.Add(NV);
        }
        static void Themkhachhang(List<Khachhang> DBDV)
        {
            Console.Write("TenKH:");
            string KH1 = Console.ReadLine();
            Console.Write("MaKH:");
            string KH2 = Console.ReadLine();
            Console.Write("GioiTinh:");
            string KH3 = Console.ReadLine();
            Console.Write("NgaySinh:");
            string KH4 = Console.ReadLine();
            Console.Write("LoaiKhachHang:");
            string KH5 = Console.ReadLine();
            Console.WriteLine("\n");
            Khachhang NV = new Khachhang(KH1, KH2, KH3, KH4, KH5);
            DBDV.Add(NV);
        }
        static void TTNV(List<NhanV> DSDV)
        {
            for (int i = 0; i < DSDV.Count; i++)
            {
                DSDV[i].infor();
            }
        }
        static void TTKH(List<Khachhang> DBDV)
        {
            for (int i = 0; i < DBDV.Count; i++)
            {
                DBDV[i].infor();
            }
        }
        static void TKKH(List<Khachhang> DBDV)
        {
            int Khachhangmoi = 0;
            int Thanhvien = 0;
            int Vip = 0;
            for (int i = 0; i < DBDV.Count; i++)
            {
                if (DBDV[i].LoaiKH == "Khachhangmoi")
                {
                    Khachhangmoi += 1;
                }
                else if (DBDV[i].LoaiKH == "Thanhvien")
                {
                    Thanhvien += 1;
                }
                else if (DBDV[i].LoaiKH == "Vip")
                {
                    Vip += 1;
                }
            }
            Console.WriteLine("so Khach hang moi: {0}", Khachhangmoi);
            Console.WriteLine("so thanh vien: {0}", Thanhvien);
            Console.WriteLine("so thanh vien vip: {0}", Vip);
        }
        static void Menu()
        {
            Console.WriteLine("Them nhan vien thi nhap ae");
            Console.WriteLine("Them khach hang thi nhap ac ");
            Console.WriteLine("hien thi thong tin nhan vien thi nhap dae ");
            Console.WriteLine("hien thi thong tin khach hang thi nhap dac ");
            Console.WriteLine("thong ke khach hang thi nhap cs ");
        }
    }
}
