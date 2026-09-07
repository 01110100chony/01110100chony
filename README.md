

<div align="center">

```c
/**
 * ════════════════════════════════════════════════════════════════
 *
 *   @file       profile.c
 *   @author     Anthony_Cristian
 *
 *   @brief      Engineer in training. Navigating the convergence of
 *               High-Performance Computing/
 *               Quantum Computing/
 *               Quantitative Finance 
 *               with focus on shaping the future infrastructure.
 *         
 * ════════════════════════════════════════════════════════════════
 */
```

</div>

---

## `// INFORMATION`

```c
#include <stdio.h>
#include <string.h>

typedef struct {
    char   *name;
    int     age;
    char   *university;
    char   *degree;
    char   *course;
    int     enrolled_since;
} Developer;

Developer me = {
    .name            = "Anthony_Cristian",
    .age             =  21,
    .university      = "UTFPR",
    .degree          =  "Bachelor",
    .course          = "Computer_Engineering",
    .enrolled_since  =  2024;
};
```

---

## `// TECHNICAL STACK`

```c
/* ── Languages ──────────────────────────────────────────────── */
typedef enum {
    C,
    CPP,        /* C++  */ //secondary
    PYTHON,
    RUST, //main
    JAVA,
    ZIG,
} ProgrammingLanguage;

/* ── Tools & Software ───────────────────────────────────────── */
typedef enum {
    /* Editors & IDEs */
    CURSOR,
    VSCODE,
    JETBRAINS,
    ZED, // my fav one

    /* Design & Media */
    DAVINCI_RESOLVE,
    FL_STUDIO,
    FIGMA,

    /* 3D / CAD / Creative Tech */
    BLENDER,
    TOUCHDESIGNER,
    AUTOCAD,
    TINKERCAD,
    FUSION_360,
    INVENTOR,

    /* Productivity */
    OBSIDIAN,
    NOTION,
    SLACK,
    REDIS,
} Tool;
```

---

## `// SPOKEN LANGUAGES`

```c
typedef struct {
    char *language;
    char *level;       
} SpokenLanguage;

SpokenLanguage languages[] = {
    { "<ENGLISH>", "<B2>" }, //c1 soon
    { "<PORTUGUESE_BRAZILIAN>", "<NATIVE>" },
    { "<SPANISH>", "<A1>" },
};
```

---


<div align="center">

```c
/* eof — profile.c */
```

</div>
