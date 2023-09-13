# -*- coding: utf-8 -*-
"""
Spyder Editor

This is a temporary script file.
"""

def gen_f(C):
    def f(x):
        return x**2-C
    return f

sandwhich = gen_f(2)
tomato = gen_f(3)
sandwhich(1)
tomato(1)
print("tomato %.3f and sandwhich %.3f"%(tomato(1),sandwhich(1)))
