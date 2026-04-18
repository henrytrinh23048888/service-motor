# Motorcycle Service Analysis Project (XE-MAY)

Project focus: Deep research, technical standardization, and localized service documentation for the Vietnamese motorcycle market.

## Key Principles
- **Deep Research First:** Always use web search to verify technical specifications, local pricing, and Vietnamese shop terminology (tiếng lóng thợ).
- **Service Standardization:** Every service MUST follow the 2-level hierarchy:
    - Level 1: Dịch vụ Cha (Broad system category).
    - Level 2: Dịch vụ Con (Specific technical action).
- **Part Group Mapping:** Map every service to one of the 59 predefined folders in `Phan_Tich_Chi_Tiet_Phu_Tung/`.
- **Localization:** Use professional Vietnamese technical terms (e.g., "Quy-lát", "Xúpap", "Dây curoa") and document local market nuances.

## Documentation Workflow
- **Service Entry:** When a new "General Name" (Tên chung chung) is provided:
    1. Research the root cause and technical procedure.
    2. Define Level 1 & Level 2 names.
    3. Identify the correct `Nhóm Phụ Tùng`.
    4. Create or update `Dich_Vu.md` in the corresponding sub-folder.
- **Table Format:** All service tables must include: `Tên Chung Chung`, `Dịch Vụ Cha (Level 1)`, `Dịch Vụ Con (Level 2)`, `Phụ Tùng & Vật Tư Liên Quan`.
- **Part Lists:** Always use bullet points for part items to ensure they are clear and concise.

## File Naming Conventions
- Root folders: `snake_case` without accents (e.g., `TRUC_CAM_XUPAP`).
- Documentation: `Dich_Vu.md` inside each part group folder.
- Mapping summary: `Phan_Tich_Chi_Tiet_Phu_Tung/Dich_Vu_Chuan_Hoa.md`.

## Commands (Reference)
- `grep -r "Dịch Vụ" .`: Search all service definitions.
- `ls Phan_Tich_Chi_Tiet_Phu_Tung/`: List all motorcycle part groups.
