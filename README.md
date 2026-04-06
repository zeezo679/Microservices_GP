# LMS Service Boundaries

> For each service, fill in what it owns, what it exposes, and what it explicitly does NOT own.
> The "Does NOT own" section is the most important — this is where we catch boundary violations before they become coupled code.
> If two people disagree about who owns something, that's a team decision to make now, not a refactoring later.

---

## Rule
If service A needs data owned by service B, it calls B's API — it never queries B's database directly.

---

## Identity Service

### Owns
- 

### Exposes
- 

### Does NOT own
- 

---

## Course Service

### Owns
- 

### Exposes
- 

### Does NOT own
- 

---

## Enrollment Service

### Owns
- 

### Exposes
- 

### Does NOT own
- 

---

## Assessment Service

### Owns
- 

### Exposes
- 

### Does NOT own
- 

---

## Progress Service

### Owns
- 

### Exposes
- 

### Does NOT own
- 

---

## Notification Service

### Owns
- 

### Exposes
- 

### Does NOT own
- 

---

## Boundary Check (fill in after everyone is done)

Go through all six documents and answer:

- Is anything owned by two services?
- Is anything owned by nobody?
- Does any service expose data it doesn't own?

Either of the first two is a problem that needs a team decision before any code is written.
