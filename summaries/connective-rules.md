- [Rules for ⋀ (and)](#rule-and)
- [Rules for ⋁ (or)](#rule-or)
- [Rules for →](#rule-arrow)
- [Rules for ¬ (not)](#rule-not)
- [Rules for ⊥ (bottom/false)](#rule-bottom)
- [Rules for ↔ (equivalent)](#rule-equivalent)

<a name="rule-and"></a>
## Rules for ⋀ (and)

#### Introduction
```java
 𝞅       ⲯ
----------- ⋀I
   𝞅 ⋀ ⲯ
```

#### Elimination
```java
 𝞅       ⲯ         𝞅       ⲯ
----------- ⋀E    ----------- ⋀E
     𝞅                 ⲯ
```

<a name="rule-or"></a>
## Rules for ⋁ (or)

#### Introduction
```java
     𝞅                 ⲯ
----------- ⋁I    ----------- ⋁I
   𝞅 ⋁ ⲯ             𝞅 ⋁ ⲯ
```

#### Elimination
```java
             𝞅 (1)   ⲯ (2)
             .       .
             .       .
 𝞅 ⋁ ⲯ       𝞂       𝞂
----------------------- ⋁E (1, 2)
             𝞂
```

Compare cases.

<a name="rule-arrow"></a>
## Rules for →

#### Introduction
```java
     𝞅 (1)
     .
     .
     ⲯ
----------- →I (1)
   𝞅 → ⲯ
```

If 𝞅 is a supposition, 𝞅 can be underlined.

#### Elimination
```java
 𝞅       𝞅 → ⲯ
--------------- →E
       ⲯ
```

<a name="rule-not"></a>
## Rules for ¬ (not)

#### Introduction
```java
     𝞅 (1)
     .
     .
     ⊥
----------- ¬I (1)
    ¬𝞅
```

#### Elimination
```java
 𝞅      ¬ⲯ
----------- ¬E
     ⊥
```

<a name="rule-bottom"></a>
## Rules for ⊥ (bottom/false)

#### RAA (Reductio Ad Absurdum)
```java
    ¬𝞅 (1)
     .
     .
     ⊥
----------- RAA (1)
     𝞅
```

<a name="rule-equivalent"></a>
## Rules for ↔ (equivalent)

#### Introduction
```java
 𝞅 → ⲯ       ⲯ → 𝞅
------------------- ↔I
       𝞅 ↔ ⲯ 
```

#### Elimination
```java
 𝞅 ↔ ⲯ         𝞅 ↔ ⲯ
------- ↔E    ------- ↔E
 𝞅 → ⲯ         ⲯ → 𝞅
```
