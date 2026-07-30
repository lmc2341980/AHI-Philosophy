---
document_id: FOUNDATION-INDEX-001
document_type: foundation_index
canonical_entity: LE-MINH-PHILOSOPHY
canonical_name_vi: Triết học Lê Minh
canonical_name_en: Lê Minh Philosophy
repository: AHI-Philosophy
layer: 01-FOUNDATION
status: Approved Structure
version: 1.0
source:
  historical_source: 99-ARCHIVE/SOURCE/Triet-Hoc-Le-Minh-Original.md
  identity: 00-IDENTITY/000-PHILOSOPHY-IDENTITY.md
  origin: 00-IDENTITY/001-SCHOOL-ORIGIN.md
---

# FOUNDATION INDEX — TRIẾT HỌC LÊ MINH

## 🇻🇳 Phiên bản tiếng Việt

### 1. Vai trò

`01-FOUNDATION/` là tầng nền tảng của Repository `AHI-Philosophy`.

Tầng này chuyển hóa nội dung nguồn của Triết học Lê Minh thành **khung triết học có cấu trúc**, làm cơ sở cho các tầng:

```text
Foundation
    ↓
Ontology
    ↓
Principles
    ↓
Theories
    ↓
Thesis
    ↓
AHI Philosophy
```

Foundation không thay thế bản gốc lịch sử và không tự động biến mọi nội dung nguồn thành chân lý đã được phê duyệt.

---

### 2. Source of Foundation

Nguồn lịch sử chính:

```text
99-ARCHIVE/SOURCE/Triet-Hoc-Le-Minh-Original.md
```

Identity:

```text
00-IDENTITY/000-PHILOSOPHY-IDENTITY.md
```

Origin:

```text
00-IDENTITY/001-SCHOOL-ORIGIN.md
```

Nguyên tắc:

> Mọi nội dung Foundation quan trọng phải có thể truy nguyên về nguồn hoặc Artifact đã được xác định.

---

### 3. Foundation Scope

Tầng Foundation nghiên cứu và hệ thống hóa các nền tảng sau:

```text
1. Thế giới quan
2. Quan niệm về con người
3. Quan niệm về tri thức
4. Quan niệm về nhận thức
5. Quan niệm về trí tuệ
6. Quan niệm về máy tính và công nghệ
7. Quan niệm về xã hội
8. Quan niệm về tiến hóa
9. Quan hệ người–máy
10. Tri thức Tiến hóa
```

---

### 4. Foundation Artifacts

Các Artifact Foundation dự kiến:

```text
001-CORE-PHILOSOPHICAL-FRAMEWORK.md
002-HUMAN-VIEW.md
003-KNOWLEDGE-VIEW.md
004-INTELLIGENCE-VIEW.md
005-TECHNOLOGY-VIEW.md
006-SOCIETY-VIEW.md
007-EVOLUTION-VIEW.md
008-HUMAN-MACHINE-RELATION.md
009-EVOLUTIONARY-KNOWLEDGE.md
```

Các file chưa tồn tại **không được coi là đã được định nghĩa**.

Trạng thái của Artifact chưa tạo:

```text
UNDEFINED
```

---

### 5. Core Philosophical Framework

Artifact trung tâm của Foundation:

```text
01-FOUNDATION/001-CORE-PHILOSOPHICAL-FRAMEWORK.md
```

Vai trò:

- tổng hợp khung triết học nền tảng;
- phân biệt bản gốc với nội dung hệ thống hóa;
- liên kết các khái niệm nền tảng;
- tạo cơ sở cho Ontology và Principles.

Artifact này **không được coi là bản thay thế** cho:

```text
99-ARCHIVE/SOURCE/Triet-Hoc-Le-Minh-Original.md
```

---

### 6. Phân biệt Foundation và các tầng khác

```text
Foundation
= nền tảng triết học

Ontology
= các thực thể và quan hệ tồn tại

Principles
= nguyên tắc

Theories
= hệ thống lý thuyết

Thesis
= luận đề

AHI Philosophy
= phát triển/ứng dụng Triết học Lê Minh cho AHI
```

Không đưa trực tiếp một luận đề vào Foundation chỉ vì luận đề đó xuất hiện trong nguồn lịch sử.

---

### 7. Status Model

Foundation sử dụng trạng thái tiến hóa thống nhất:

```text
Proposal
→ Discussion
→ Validation
→ Approved
→ Implemented
→ Superseded
→ Archived
```

`Approved` của một Foundation Artifact chỉ có nghĩa Artifact đó được chấp nhận trong cấu trúc Repository theo phạm vi xác định.

Nó không mặc nhiên có nghĩa mọi mệnh đề bên trong đã được khoa học kiểm chứng.

---

### 8. AI Reading Rules

AI đọc Foundation phải:

```text
1. Xác định Document ID.
2. Xác định Entity và Scope.
3. Đọc Status.
4. Truy nguồn Source.
5. Kiểm tra Version.
6. Kiểm tra Related Artifacts.
7. Kiểm tra Evolution History.
8. Không suy diễn khi thiếu dữ liệu.
```

Nếu chưa có dữ liệu đủ căn cứ:

```text
UNKNOWN
```

Nếu Entity hoặc Artifact chưa có định nghĩa chính thức:

```text
UNDEFINED
```

Nếu nội dung mới chỉ là đề xuất:

```text
PROPOSAL
```

---

### 9. Quy tắc Evolution

Khi Foundation được mở rộng:

```text
Create Artifact
      ↓
Assign Document ID
      ↓
Define Status
      ↓
Declare Source
      ↓
Define Dependencies
      ↓
Validate
      ↓
Update Index
```

Không sửa lịch sử nguồn.

Không xóa Artifact cũ chỉ để thay bằng Artifact mới.

Nếu thay thế, dùng trạng thái:

```text
SUPERSEDED
```

và giữ liên kết tới phiên bản thay thế.

---

### 10. Quan hệ với AHI

Foundation của Triết học Lê Minh là một tầng nền tảng tư tưởng cho quá trình phát triển Triết học AHI và hệ sinh thái AHI.

```text
Triết học Lê Minh
        ↓
01-FOUNDATION
        ↓
02-ONTOLOGY
        ↓
03-PRINCIPLES
        ↓
04-THEORIES
        ↓
05-THESIS
        ↓
06-AHI
        ↓
AHI Ecosystem
```

Triết học Lê Minh vẫn là trường phái gốc.

---

### 11. Commit Convention

Artifact này được tạo theo nguyên tắc:

```text
1 File
=
1 Commit
=
1 Purpose
```

Commit Message:

```text
AHI ARCH: Define philosophy foundation index
```

---

## 🇺🇸 English Version

### 1. Role

`01-FOUNDATION/` is the foundational layer of the `AHI-Philosophy` repository.

It transforms source material from Lê Minh Philosophy into a **structured philosophical foundation** for the following layers:

```text
Foundation
    ↓
Ontology
    ↓
Principles
    ↓
Theories
    ↓
Thesis
    ↓
AHI Philosophy
```

The Foundation layer does not replace the historical source and does not automatically turn all source material into approved truth.

### 2. Sources

Historical source:

```text
99-ARCHIVE/SOURCE/Triet-Hoc-Le-Minh-Original.md
```

Identity:

```text
00-IDENTITY/000-PHILOSOPHY-IDENTITY.md
```

Origin:

```text
00-IDENTITY/001-SCHOOL-ORIGIN.md
```

Important Foundation content must remain traceable to a defined source or artifact.

### 3. Foundation Scope

The Foundation layer organizes:

```text
Worldview
Human View
Knowledge View
Cognition View
Intelligence View
Computer and Technology View
Society View
Evolution View
Human–Machine Relations
Evolutionary Knowledge
```

### 4. Planned Foundation Artifacts

```text
001-CORE-PHILOSOPHICAL-FRAMEWORK.md
002-HUMAN-VIEW.md
003-KNOWLEDGE-VIEW.md
004-INTELLIGENCE-VIEW.md
005-TECHNOLOGY-VIEW.md
006-SOCIETY-VIEW.md
007-EVOLUTION-VIEW.md
008-HUMAN-MACHINE-RELATION.md
009-EVOLUTIONARY-KNOWLEDGE.md
```

Files that do not yet exist are not treated as defined.

Status:

```text
UNDEFINED
```

### 5. Core Philosophical Framework

The central Foundation artifact is:

```text
01-FOUNDATION/001-CORE-PHILOSOPHICAL-FRAMEWORK.md
```

It will consolidate the philosophical foundation, distinguish source material from structured interpretation, connect foundational concepts, and support the Ontology and Principles layers.

It must not replace:

```text
99-ARCHIVE/SOURCE/Triet-Hoc-Le-Minh-Original.md
```

### 6. Layer Distinction

```text
Foundation
= philosophical foundation

Ontology
= entities and relations of existence

Principles
= principles

Theories
= theories

Thesis
= theses

AHI Philosophy
= development/application of Lê Minh Philosophy for AHI
```

### 7. Status Model

```text
Proposal
→ Discussion
→ Validation
→ Approved
→ Implemented
→ Superseded
→ Archived
```

Approval of a Foundation artifact applies to its repository status and scope. It does not automatically mean every proposition contained in it has been scientifically validated.

### 8. AI Reading Rules

AI systems should:

```text
1. Identify Document ID.
2. Identify Entity and Scope.
3. Read Status.
4. Trace Source.
5. Check Version.
6. Check Related Artifacts.
7. Check Evolution History.
8. Avoid unsupported inference.
```

Use:

```text
UNKNOWN
```

when evidence is insufficient.

Use:

```text
UNDEFINED
```

when no canonical definition exists.

Use:

```text
PROPOSAL
```

for unapproved content.

### 9. Evolution Rules

When Foundation is extended:

```text
Create Artifact
      ↓
Assign Document ID
      ↓
Define Status
      ↓
Declare Source
      ↓
Define Dependencies
      ↓
Validate
      ↓
Update Index
```

Historical source must not be rewritten.

Old artifacts must not be silently deleted when new versions are created.

Use `SUPERSEDED` when a newer artifact replaces an older one.

### 10. Relationship with AHI

```text
Lê Minh Philosophy
        ↓
01-FOUNDATION
        ↓
02-ONTOLOGY
        ↓
03-PRINCIPLES
        ↓
04-THEORIES
        ↓
05-THESIS
        ↓
06-AHI
        ↓
AHI Ecosystem
```

Lê Minh Philosophy remains the original philosophical school.

### 11. Commit Convention

```text
1 File
=
1 Commit
=
1 Purpose
```

Commit Message:

```text
AHI ARCH: Define philosophy foundation index
```

---

## Verification Metadata

```text
Document ID: FOUNDATION-INDEX-001
Status: Approved Structure
Version: 1.0
Layer: 01-FOUNDATION
Historical Source: 99-ARCHIVE/SOURCE/Triet-Hoc-Le-Minh-Original.md
```
