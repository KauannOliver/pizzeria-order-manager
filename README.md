# Pizzeria Order Manager

A desktop application for managing customers, menu items, and orders, with spreadsheet exports and a browser-assisted WhatsApp workflow.


## Capabilities

- Create, view, update, and remove customer, pizza, and order records.
- Persist application data in SQLite.
- Export operational data with Pandas and OpenPyXL.
- Open WhatsApp order conversations through a browser workflow.

## Stack

Python, Flet, SQLite, Pandas, OpenPyXL, Requests, Selenium, and FPDF.

## Run locally

Requires Python and the dependencies listed in `requirements.txt`. Run `pip install -r requirements.txt`, then `python main.py`. The database tables are initialized locally by the application. Customer databases and receipts are excluded from this public edition; use synthetic records for demonstrations.


## Snapshot review

Optional WhatsApp browser automation depends on manual login and browser compatibility. Set `FIREFOX_PROFILE_DIR` only to a dedicated local test profile; personal browser profiles are not distributed.

Git-triggered Vercel deployment is disabled in the included web configurations. This update publishes source and documentation only.

## License

Original application code is available under the [MIT license](LICENSE). Third-party libraries, models, fonts and bundled assets retain their own licenses.

## Verification record

See [snapshot checks and remaining limitations](docs/VERIFICATION.md).
