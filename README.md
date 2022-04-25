# Digital-Night-Vision-Project

This repository is for instructions and documentation on building a digital night vision monocular.

Parts list:

NTSC/PAL 2.0" display: https://www.adafruit.com/product/911 Digikey: https://www.digikey.com/en/products/detail/adafruit-industries-llc/911/7241440

FPV NTSC/PAL camera module: https://www.ebay.com/itm/264788921721

Fixed output Voltage regulator: https://www.digikey.com/en/products/detail/stmicroelectronics/L7805CV-DG/2832888

Rocker Switch: https://www.digikey.com/en/products/detail/zf-electronics/SRB22A2FBBNN/446021

Mini Protoboard: https://www.digikey.com/en/products/detail/sparkfun-electronics/PRT-08808/7387401

Bud Box: https://www.digikey.com/en/products/detail/bud-industries/CU-1874-B/387084 **i would recommend getting a slightly larger box if you do not have a dremel tool since the display does not clear the top and bottom of this box**

Bi Convex lens: https://www.amazon.com/gp/product/B00EPQ9EVQ/ref=oh_aui_detailpage_o07_s01?ie=UTF8&psc=1

Infared Torch: https://www.amazon.com/MAKE-ONE-IR-Infrared-Flashlight/dp/B016ZPH470

Green acrylic sheet(for green effect) https://www.ebay.com/itm/323428150170?chn=ps&norover=1&mkevt=1&mkrid=711-117182-37290-0&mkcid=2&itemid=323428150170&targetid=1262779891809&device=c&mktype=&googleloc=9015334&poi=&campaignid=14859008593&mkgroupid=130497710760&rlsatarget=pla-1262779891809&abcId=9300678&merchantid=101988463&gclid=Cj0KCQiAoNWOBhCwARIsAAiHnEit7RGGvpWTUU-Ul6mgzCwe9dbJbK94pMc1bjWlTdAf5dz6mOS95OkaAgs0EALw_wcB

This is all powered by a simple 9v battery (ir torch pwr is AA)


Pictures of building the night vision monocular:


![wire diagram](https://user-images.githubusercontent.com/88860704/154828963-3bec6a4f-52d8-4df6-91f0-3091d434657d.jpg)
^wireing diagram
![20211230_192737](https://user-images.githubusercontent.com/88860704/154826993-cd2bea1e-57a1-4f8a-bb8d-0f6d05f5a97b.jpg)
^breadboard config for testing 
**NOTE: on the display the video signal wires might be yellow and white or black and yellow. dispite yellow being the color for the video signal in, it is always going to be the wire farthest to the right(looking up). in my case yellow ended up being GND which caused many issues**

also consult the docs for the voltage regulator for specifics but left is always input, middle is GND, and right output.

![20220129_215206](https://user-images.githubusercontent.com/88860704/158042709-df2bc04e-e32b-4c79-8280-f0e88fed5af5.jpg)
soldered protoboard layout
![20220105_222737](https://user-images.githubusercontent.com/88860704/161360849-16731ea2-43e5-4e14-abcb-91b24818c51f.jpg)
above is the camera module. you must remove the IR filter which is located on the lens.
![20220216_181538](https://user-images.githubusercontent.com/88860704/165013668-85671f84-c2ec-4734-b83a-38e81b47f053.jpg)
then drill out the holes in the case. and mount the switch

![20220218_230405](https://user-images.githubusercontent.com/88860704/165013724-137e62c2-d587-4021-bc00-c29a93d7e085.jpg)
and then mount components inside case
![20220224_190421](https://user-images.githubusercontent.com/88860704/165014739-422a5241-cd3f-4af5-952e-f93e65f30e9c.jpg)
![20220224_190419](https://user-images.githubusercontent.com/88860704/165014755-90038420-80a9-4048-99f5-dac17e31f1d0.jpg)
![20220224_190425](https://user-images.githubusercontent.com/88860704/165014742-ada490d2-b1dc-4fcf-b65e-17e9f302e12d.jpg)
![20220224_190431](https://user-images.githubusercontent.com/88860704/165014747-08c744ce-d309-4a94-8f56-567ee1ad4874.jpg)
![20220224_190507](https://user-images.githubusercontent.com/88860704/165014748-f26f65dd-136f-4267-b50a-201776150179.jpg)
![20220224_190519](https://user-images.githubusercontent.com/88860704/165014751-05b2e3d9-6dab-4584-a064-9f1f9482fd50.jpg)
other pictures

