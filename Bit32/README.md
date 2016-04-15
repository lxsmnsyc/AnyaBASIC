
	Bitwise Operations for 32-bit signed ints by Alexis Munsayac (github.com/LXSMNSYC)
		Language : AnyaBASIC

	provides the following functions and tables:
		tables:
			SXOR (4 - bit)
			SAND (4 - bit)
			SOR  (4 - bit)
			left (4 - bit)
			right (4- bit)
			shift (32-bit)

		functions:
			Not4(a)
				- performs a 4-bit NOT operation on int a
			And4(a, b)
				- 4-bit AND (a AND b)
			Or4(a, b)
				- 4-bit OR (a OR b)
			Xor4(a, b)
				- 4-bit XOR (a XOR b)

			Not8(a)
			And8(a, b)
			Or8(a, b)
			Xor8(a, b)

			Not16(a)
			And16(a, b)
			Or16(a, b)
			Xor16(a, b)

			Not32(a)
			And32(a, b)
			Or32(a, b)
			Xor32(a, b)

			LShift(a, shifts)
			RShift(a, shifts)

			LRot(a, shifts)
			RRot(a, shifts)

	Variables and functions names(to prevent collision, you should name your variables and functions not equal to the ff):
		Variables:
			SXOR
			SOR
			SAND
			left
			right
			shift
			
		Functions:
			All functions mentioned in the list.
