# platonic_solids_faces_function
platonic solids faces function

    b=lambda x:((x/(0**(x**2)+x))*2)**((x-1)**(x/(0**(x**2)+x)))*2+4

    map(b, range(5))

Result:
    [4, 6, 8, 12, 20]

This groovy little function returns 0 for 0 but 1 for everything else:

    x/(0**(x**2)+x)

it provides a way to avoid divide by zero errors among other things.

