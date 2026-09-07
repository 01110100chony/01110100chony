

<div align="center">

```c
/**
 * ════════════════════════════════════════════════════════════════
 *
 *   @file       profile.c
 *   @author     Anthony_Cristian
 *
 *   @brief      Engineer in training. Navigating the convergence of
 *               High-Performance Computing and Quantum Computing to
 *               rethink how financial infrastructure is built and secured.
 *
 *   @mission    Post-Quantum Cryptography is not just a theoretical
 *               challenge — it is the final frontier for preserving
 *               data integrity at scale.
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
    .age             =  20,
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
    CPP,        /* C++  */
    PYTHON,
    RUST,
} ProgrammingLanguage;

/* ── Platforms ──────────────────────────────────────────────── */
typedef enum {
    WINDOWS,
    LINUX,
} Platform;

/* ── Tools & Software ───────────────────────────────────────── */
typedef enum {
    /* Editors & IDEs */
    CURSOR,
    VSCODE,
    JETBRAINS,

    /* Design & Media */
    PHOTOSHOP,
    DAVINCI_RESOLVE,
    FL_STUDIO,

    /* 3D / CAD / Creative Tech */
    TOUCHDESIGNER,
    AUTOCAD,
    TINKERCAD,
    FUSION_360,
    INVENTOR,

    /* Productivity */
    GOOGLE_SUITE,
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
    { "<ENGLISH>", "<B2>" },
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
