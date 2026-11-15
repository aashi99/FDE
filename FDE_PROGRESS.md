 # FDE Learning Progress

**Last Updated:** 15 November 2026

## 1. Overall Progress

- **Total curriculum:** 30 hours
- **Completed:** 0 hours
- **Remaining:** 30 hours
- **Current phase:** Python for AI Engineering
- **Current session:** Session 1 — Python Essentials
- **Current status:** In Progress

> Learning approach: Accelerate familiar programming concepts using Java comparisons, but do not skip Python-specific fundamentals or built-in methods.

## 2. Curriculum Tracker

| Phase | Topic | Allocated Hours | Status |
|---|---|---:|---|
| 1 | Python for AI Engineering | 5 | In Progress |
| 2 | Core LLM Concepts | 5 | Not Started |
| 3 | RAG Systems | 8 | Not Started |
| 4 | AI Pipelines and Orchestration | 6 | Not Started |
| 5 | Production Engineering and FDE Skills | 6 | Not Started |
| | **Total** | **30** | |

## 3. Session Tracker

| Session | Topic | Status | Hours Credited |
|---|---|---|---:|
| 1 | Python Essentials | In Progress | 0 |
| 2 | Python APIs and Async | Not Started | 0 |
| 3 | LLM Fundamentals | Not Started | 0 |

The Python phase may be completed faster than its five-hour allocation if practical exercises demonstrate sufficient understanding. Any saved time can be reallocated to higher-value AI engineering topics.

## 4. Session 1 — Python Essentials

### Concepts Introduced

All concepts below are currently **In Progress**, not Mastered.

#### Variables and Data Types
- Variables and dynamic typing
- `str`, `int`, `float`, `bool`
- `type()`
- Python booleans: `True` and `False`

#### Lists
- Creating lists
- Zero-based indexing
- `len()`
- `append()`
- `remove()`
- `pop()`
- `insert()`

#### Dictionaries
- Key-value pairs
- Accessing and updating values
- `get()`
- Default values with `get(key, default)`
- `len(dictionary)` counts keys

#### Loops and Iteration
- `for` loops
- `in` keyword
- `range()`
- `range(start, stop, step)`
- Index-based iteration
- `enumerate()`
- Membership testing using `in`
- Conditional logic inside loops
- Python indentation and block structure

#### String Operations
- `upper()`
- `lower()`
- `startswith()`
- `endswith()`
- `strip()`
- Difference between Python and Java method names

#### List Comprehensions
- Filtering elements
- Transforming elements
- Combining filtering and transformation

### Java-to-Python Comparisons Covered

| Java | Python |
|---|---|
| `ArrayList.add(x)` | `list.append(x)` |
| `ArrayList.remove(x)` | `list.remove(x)` |
| `list.get(i)` | `list[i]` |
| `list.size()` | `len(list)` |
| `HashMap.get(key)` | `dict.get(key)` |
| `HashMap.getOrDefault(k, v)` | `dict.get(k, v)` |
| Enhanced for loop | `for item in collection:` |
| `collection.contains(x)` | `x in collection` |

## 5. Exercises Pending

These exercises must be attempted and reviewed before Session 1 can be marked complete.

1. **String immutability:** Predict the output of `name.upper()` and explain whether the original string changes.
2. **List operations:** Independently implement list addition and removal using Python methods.
3. **Document filtering:** Filter PDF files from a list using a normal `for` loop and `if` condition, then convert matching filenames to uppercase.
4. **List comprehension:** Implement the same PDF filtering and uppercase transformation using a list comprehension.

### Next Learning Topics

After completing the pending exercises:

- Python functions and return values
- Tuples and sets
- Exception handling
- File handling
- JSON parsing and serialization
- Python modules and imports
- Virtual environments and package management
- Type hints
- Pydantic fundamentals
- Async programming and API integration

## 6. Project Progress — Enterprise Document Intelligence Platform

**Repository:** [https://github.com/aashi99/FDE](https://github.com/aashi99/FDE)

### Planned Components

| Component | Status |
|---|---|
| Document ingestion | Not Started |
| Document parsing | Not Started |
| Chunking and metadata extraction | Not Started |
| Embedding generation | Not Started |
| Vector database | Not Started |
| Hybrid retrieval | Not Started |
| Reranking | Not Started |
| LLM question answering with citations | Not Started |
| Evaluation and quality metrics | Not Started |
| Workflow orchestration and tool calling | Not Started |
| FastAPI backend | Not Started |
| Docker deployment | Not Started |
| Logging and observability | Not Started |
| Security and cost optimization | Not Started |

### Current Implementation Status

- GitHub repository exists.
- Python document metadata and filtering examples have been introduced during learning.
- No independently implemented and verified project component has been completed yet.

## 7. Concepts Mastered

None yet.

A concept will be marked Mastered only after the learner demonstrates understanding through explanation or implementation.

## 8. Concepts Requiring Revision

- Python dictionary length and key counting.
- String immutability and return values of string methods.
- List operations and their differences.
- List comprehensions.

## 9. Open Questions and Decisions

### Learning Decisions
- Use Python for all AI engineering implementations.
- Use Java comparisons to accelerate familiar programming concepts.
- Explain Python built-in methods before expecting their use.
- Prefer practical implementation over passive reading.
- Do not mark topics mastered without testing.
- Do not credit hours based only on explanations.

### Environment
- Development machine: Mac with ARM64 architecture.
- Docker Desktop installation guidance was discussed.
- Docker is not required for the current Python fundamentals exercises.

### Open Questions
- Complete pending Session 1 exercises.
- Set up the Python development environment for the project.
- Decide on the vector database and embedding provider when the RAG phase begins.

## 10. Next Session

**Resume:** Session 1 — Python Essentials

**Start with:** String immutability exercise.

Then complete the remaining list and document-filtering exercises before moving to Python functions and other foundational topics.

## 11. Progress Update History

### 15 November 2026
- Started Session 1: Python Essentials.
- Covered variables, data types, lists, dictionaries, loops, iteration, range, enumerate, string methods and list comprehensions.
- Agreed on an accelerated Python learning approach using Java comparisons.
- Session remains In Progress.
- Hours credited: 0.
