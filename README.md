# Fyne Markdown Editor

A sleek and efficient Markdown editor built using Fyne and Go. It provides a user-friendly interface for creating and editing Markdown documents, leveraging the power and simplicity of Fyne's UI toolkit combined with the performance of Go. 📝📄

**About this Repository**<br />
🌐 Introduction project of the _[Building GUI Applications with Fyne and Go](https://www.udemy.com/course/building-gui-applications-with-fyne-and-go-golang/?couponCode=KEEPLEARNING)_ course.<br />
⭐ Building a Markdown Editor in Fyne (with Go)<br />
🔍 Creating Menu Items, Saving & Opening Files and Themes!

## Start the application

To start the application, ensure you have both Fyne and Go installed on your system. You can refer to the official documentation for installation instructions:

- [Fyne Documentation](https://docs.fyne.io/) - Easily Build Native Apps that Work Everywhere
- [Go Programming Language](https://go.dev/) - Build Simple, Secure and Scalable systems

If you are using [asdf](https://asdf-vm.com/), you can also install Go via the _.tool-versions_ file. More information on this can be found [here](https://asdf-vm.com/manage/configuration.html#tool-versions).<br />
Once Go and Fyne are installed, follow these steps to start the application:

```bash
git clone https://github.com/ThomasCode92/hello-fyne
cd hello-fyne     # navigate into project folder
go run .          # start the program
```

To run the tests, use the command `go test -v .`.

### Build the application

Ensure the _fyne command_ installed before compiling and building the application. When using _asdf_, reshim golang after the installation. To install the fyne command, use this command:<br />
`go install fyne.io/fyne/v2/cmd/fyne@latest`.

Then, to build the application for your operating system, run:<br />
`fyne package -appVersion 1.0.0 -name Fyne-MD -release`.
