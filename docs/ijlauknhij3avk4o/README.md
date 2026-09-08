# Kawangware Barber price page

Open `index.html` in any modern phone or computer browser. The green button shares the visible price list through the phone's share menu or opens WhatsApp with the message already prepared.

To change a service or price, edit the text inside the matching `service-name` or `service-price` span in `index.html`. The WhatsApp message is built from those visible rows, so it stays in sync automatically.

Run the checks with:

```sh
python3 -m unittest discover -s tests -v
```
