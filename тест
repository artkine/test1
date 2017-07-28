using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace LibraryClass
{
    public class Class1
    {
        public static bool calc_90(double a, double b, double c)
        {
            bool res = true;
            if (c > a && c > b)
            {
                if (Math.Pow(c, 2) == (Math.Pow(a, 2) + Math.Pow(b, 2)))
                    res = true;
                else
                    res = false;
            }
            else
                res = false;
            return res;
        }
        public static double calc_treug(double a, double b, double c)
        {
            double S = 0;
            if (calc_90(a, b, c))
                S = 0.5 * a * b;
            return S;
        }
    }
}
