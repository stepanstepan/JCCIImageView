# JCCIImageView
An image view for rendering CIImage with Metal/OpenGL/CoreGraphic. Available on iOS and OS X. Written in Swift.

```
let imageView = JCCIImageView(frame: CGRect(x: 50, y: 50, width: 300, height: 300))
imageView.renderer = JCCIImageViewSuggestedRenderer()
imageView.image = CIImage(color: CIColor.black).cropped(to: CGRect(x: 0, y: 0, width: 300, height: 300))

```
