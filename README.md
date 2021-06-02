# SPRING MEDIA

#### Video Demo: <https://youtu.be/5GyiR1ST9Oc>

#### Description

Spring media filter is a tool to apply filters such as negative, sepia, blur, reflect, grayscale, etc. to your images and to detect the mimetype of a file.

Mimetype is a standard notation that indicates the type and the subtype of a file. Imagina that you have a file without any extension as ".jpg", ".txt", ".exe", ".zip", etc. without a valid extension maybe your apps cannot use file because they don't know what type of file it is, but you could use the detect section of my app to detect the mimetype and the extension of that file.

[Here is more information about mimetypes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types "MDN - mimetype")

## How is my app made?

My application has 2 parts, backend and frontend. The backend handles all requests and maps them based on user input and the frontend is the graphic interface to communicate with the backend in an easy way to the user.

### What tools did I use to make my app?

### Frontend

* Angular
* MDBootstrap
* Angular material

#### [Frontend repo](https://github.com/lsandoval9/spring-media-frontend)

### Backend

* Spring boot (a java framework)
* Apache Tika (tool to manipulate metadata, I used it to detect the mimetypes based of the file's content)

#### [Backend repo](https://github.com/lsandoval9/spring-media-backend)

```java

    System.out.println("Thanks to the entire CS50x team for this awesome CS course!")
```
