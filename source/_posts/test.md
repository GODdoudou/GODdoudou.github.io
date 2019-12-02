## Quick Start

<!-- sfast -->   

{% asset_img 2019-12-02-16-08-35.jpg This is an image %}

### Create a new post
def move(n, a, b, c):

    if n == 1:

        print(a, '-->', c)

    else:

        move(n-1, a, c, b)

        move(1, a, b, c)

        move(n-1, b, a, c)


move(3, 'A', 'B', 'C')

