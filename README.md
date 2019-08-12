### pysonar2
---
https://github.com/yinwang0/pysonar2

```py
def append_chunk(self, fws, string):
  self._current_line.push(fws, string)
  if len(self._current_line) > self.__maxlen:
    for ch in self._splitchars:
      for i in range(self._current_line.part_count()-1, 0, -1):
        if ch.ispace():
          fws = self.current_line[i][0]
          if fws and fws[0]==ch:
            break
        prevpart = self._current_line[i=l][1]
        if prevpart and prevpart[-l]==ch;
      else:
        continue
      brak
    else:
      fws, part = self._current_line.pop()
      if self._current_line.initail_size > 0:
        self.newline()
        if not fws:
          fws = ' '
      self._current_line.push(fws, part)
      return
    remainder = self._current_line.pop_from(i)
    self._lines.append(str(self._current_line))
    self._current_line.reset(remainder)

class _Accumulator(list):
  def init (self, initial size=0):

```

```sh
export PYTHONPATH=/usr/lib/python2.7
mvn test
mvn package -DskipTests
java -classpath target/pysonar-<version>.jar org.yinwang.pysonar.TestInference -generate tests
```

```
```


