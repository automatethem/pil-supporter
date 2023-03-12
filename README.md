# pil-helper

Supported APIs
<pre>
import pil_helper

pil_helper.utils.draw_rect(image, point1, point2)
pil_helper.utils.draw_label(image, text, point, font_color=(255, 255, 255), font_size=28)
pil_helper.utils.draw_rect_with_label(image, point1, point2, text, font_color=(255, 255, 255), font_size=28)
pil_helper.utils.draw_point(image, point)
pil_helper.utils.draw_image(image, image_to_draw, point)

pil_helper.utils.crop_center(image_file, left, top, right, bottom)
pil_helper.utils.create_dummy_image(size, image_file, background_color=(255, 255, 255))
pil_helper.utils.read_from_image_file(image_file)
</pre>
