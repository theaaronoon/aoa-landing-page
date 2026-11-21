AOA Real Estate landing page
============================

Upload everything in this folder (index.html and the assets folder) to the
root of your web host. Nothing needs building.

Settings live at the bottom of index.html, in the CONFIG block:

  PIXEL_ID     Your Meta pixel ID. Leave empty and no pixel loads.
  BOOKING_URL  Calendly, Cal.com or Google appointment page link. When set,
               the calendar replaces the WhatsApp booking card.
  VIDEO_URL    YouTube embed link (https://www.youtube.com/embed/VIDEO_ID)
               or an .mp4 file. Leave empty and a placeholder box shows.
  WHATSAPP     Number that WhatsApp buttons open (country code, no +).
  WA_MESSAGE   Text pre-filled in the WhatsApp chat.

Pixel events sent once PIXEL_ID is set:
  PageView       on load
  Contact        when a WhatsApp button is tapped
  Schedule       when a Calendly or Cal.com booking completes
  BookCTAClick   (custom) when a "Book" button is tapped
  ReviewOpen     (custom) when a review is opened full size
  VideoPlay      (custom) when an .mp4 video starts

Your photo is assets/aaron.jpg. Replace that file to change it.
