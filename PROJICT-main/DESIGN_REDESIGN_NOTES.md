# Modern minimalist GUI refresh

This version refreshes the existing **Pearl’s SigNAILture** PyQt6 desktop UI across admin, staff, and customer roles. It retains all application modules, navigation targets, business logic, models, database code, and service calls.

## Changes
- Unified neutral light background, white content surfaces, slate text, and muted blue-gray accents.
- Updated navigation buttons, hover/selected states, and sidebar width for easier scanning.
- Consistent form controls, primary/destructive buttons, focus states, and disabled states.
- Updated tables, headers, tabs, lists, dialogs, gallery cards, and scrollbars.
- Increased shared window padding and spacing.

## Running
```bash
python -m pip install -r requirements.txt
python main.py
```

## Notes
- Some screens set their own inline widget styles; those may take precedence over the global stylesheet.
- This is a source-level GUI refresh, **not** a verified end-to-end runtime test. PyQt6 is not installed in the build environment. Test appointment, queue, loyalty, payment, and role flows locally before deployment.
