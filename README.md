# python_things
Learning python

# def quicksort(arr):
	# if len(arr) <= 1:
		# return arr
	# pivot = arr[len(arr) / 2]
	# left = [x for x in arr if x < pivot]
	# middle = [x for x in arr if x == pivot]
	# right = [x for x in arr if x > pivot]
	# return quicksort(left) + middle + quicksort(right)
	
# print quicksort([3,6,8,10,1,2,1])

# x = 3
# print type(x)
# print x
# print x + 1
# print x - 1
# print x * 2
# print x ** 2
# x += 1
# print x
# x *= 2
# print x
# y = 2.5
# print type(y)
# print y,y+1,y*2,y**2

# t = True
# f = False
# print type(t)
# print t and f
# print t or f
# print not t
# print t != f

# hello = 'hello'
# world = "world"
# print hello
# print len(hello)
# hw = hello + ' ' + world 
# print hw
# hw12 = '%s %s %d' % (hello,world,12)
# print hw12 
# hw23 = hello + ' ' + world + ' ' + str(23)
# print hw23

# s = "hello"
# print s.capitalize()
# print s.upper()
# print s.rjust(7)
# print s.center(7)
# print s.replace('l','(ell)')
# print '  world '.strip()

# xs = [3,1,2]
# print xs, xs[2]
# print xs[0]
# print xs[-1]
# xs[2] = 'foo'
# print xs
# xs.append('bar')
# print xs
# x = xs.pop()
# print x,xs

# nums = range(5)
# print nums 
# print nums[2:4] #exclusive
# print nums[2:]
# print nums[:2]
# print nums[:]
# print nums[:-1]
# nums[2:4] = [8,9]
# print nums

# animals = ['cat', 'dog', 'monkey']
# for animal in animals:
	# print animal

# animals = ['cat','dog','monkey']
# for idx, animal in enumerate(animals):
	# print '#%d: %s' % (idx+1,animal)

# nums = range(5) #nums = [0,1,2,3,4] 
# squares = []
# for x in nums:
	# squares.append(x**2)
# print squares

## Can be done as:
# nums = range(5)
# squares = [x**2 for x in nums]
# print squares

# nums = range(5)
# even_squares = [x**2 for x in nums if x%2 == 0]
# print even_squares

## (KEY,VALUE)
# d = {'cat': 'cute', 'dog': 'furry'}
# print d['cat']
# print 'cat' in d
# d['fish'] = 'wet'
# print d['fish']
# print d.get('monkey','N/A') #N/A is default
# print d.get('fish','N/A')
# del d['fish']
# print d.get('fish','N/A')

# d = {'person': 2, 'cat': 4, 'spider': 8}
# for animal in d:
	# legs = d[animal]
	# print 'A %s has %d legs' % (animal,legs)

# d = {'person': 2, 'spider': 8, 'cat': 4}
# for animal, legs in d.iteritems():
	# print 'A %s has %d legs' % (animal,legs)

## No va 
# nums = range(5)
# even_num_to_square = {x: x**2 for x in nums if x%2==0}
# print even_num_to_square

## No va
# animals = {'cat', 'dog'}
# print 'cat' in animals
# print 'fish' in animals
# animals.add('fish')
# print fish in animals
# animals.add('cat') #Does nothing
# print len(animals)
# animals.remove('cat')
# print len(animals)

## No va
# animals = {'cat','dog', 'fish'}
# for idx, animal in enumerate(animals):
	# print '#%d: %s' % (idx+1,animal)
	
# from math import sqrt
# nums = {int(sqrt(x)) for x in range(30)}
# print nums
