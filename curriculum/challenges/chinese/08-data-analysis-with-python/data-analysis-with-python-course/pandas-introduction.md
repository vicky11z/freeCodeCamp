---
id: 5e9a093a74c4063ca6f7c158
challengeType: 11
videoId: 0xACW-8cZU0
---

# --description--

More resources:

\- [Notebook](https://notebooks.ai/rmotr-curriculum/freecodecamp-intro-to-pandas-902ae59b)

# --question--

## --text--

What will the following code print out?

```py
import pandas as pd

certificates_earned = pd.Series(
    [8, 2, 5, 6],
    index=['Tom', 'Kris', 'Ahmad', 'Beau']
)

print(certificates_earned)
```

## --answers--

```
Tom      8
Kris     2
Ahmad    5
Beau     6
dtype: int64
```

---

```
Kris     2
Ahmad    5
Beau     6
Tom      8
dtype: int64
```

---

```
Tom      8
Kris     2
Ahmad    5
Beau     6
Name: certificates_earned dtype: int64
```

## --video-solution--

1

# --hints--


# --solutions--

