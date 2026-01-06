# program-39
def strip_chars(str,chars):
return"".join(c for c in str if c not in chars)
print("\n original string:")
print("the quick brown fox jumps over the lazy dog")
print("after stripping a,e,i,o,u")
print(strip_chars("the quick brown fox jumps over the lazy dog","aeiou"))
print()
Output:
original string:
the quick brown fox jumps over the lazy dog
after stripping a,e,i,o,u
th qck brwn fx jmps vr th lzy dg
