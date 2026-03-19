import flet as ft

def main(page: ft.Page):
    page.title = "Lujen Alhaj 👩🏻‍💻✨"
    
    # Header
    page.add(
        ft.Column(
            [
                ft.Text("Lujen Alhaj 👩🏻‍💻✨", size=40, weight=ft.FontWeight.BOLD, text_align=ft.TextAlign.CENTER),
                ft.Text("Full-Stack Developer | AI Enthusiast | Software Engineer 🚀", size=20, text_align=ft.TextAlign.CENTER),
                ft.Image(
                    src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=600&size=24&pause=1000&color=F472B6&center=true&vCenter=true&width=850&lines=Computer+Science+Graduate+🎓;Jordan+University+of+Science+and+Technology+🏛️;Full-Stack+Developer+💻;AI+%7C+Smart+Systems+%7C+Healthcare+Tech+🩺;Building+Elegant+and+Intelligent+Solutions+✨",
                    width=850,
                ),
            ],
            alignment=ft.MainAxisAlignment.CENTER,
            horizontal_alignment=ft.CrossAxisAlignment.CENTER,
        )
    )

    # About Me
    page.add(
        ft.Column(
            [
                ft.Text("👩🏻‍💻 About Me", size=30, weight=ft.FontWeight.BOLD),
                ft.Text("🎓 Computer Science Graduate – Jordan University of Science and Technology"),
                ft.Text("💻 Full-Stack Developer (Front-End & Back-End)"),
                ft.Text("🤖 Passionate about Artificial Intelligence & Smart Systems"),
                ft.Text("🩺 Experienced in building healthcare-related systems"),
                ft.Text("🌷 Strong believer in discipline, growth, and elegant design"),
                ft.Text("🚀 Focused on creating impactful, real-world software"),
                ft.Text("\nI don’t just write code — I design experiences, architect solutions, and build systems that matter."),
            ],
            spacing=5
        )
    )

    # Core Technologies
    page.add(
        ft.Column(
            [
                ft.Text("🛠 Core Technologies", size=25, weight=ft.FontWeight.BOLD),
                ft.Image(
                    src="https://skillicons.dev/icons?i=html,css,js,python,fastapi,postgres,git,github,docker,linux,cpp,vscode",
                    width=700
                )
            ],
            spacing=10
        )
    )

    # Vision
    page.add(
        ft.Column(
            [
                ft.Text("💎 Vision", size=25, weight=ft.FontWeight.BOLD),
                ft.Text(
                    "To become a Software Engineer who merges intelligence with elegance "
                    "and builds systems that improve lives through technology 🌍✨"
                ),
            ],
            spacing=5
        )
    )

    # Footer
    page.add(
        ft.Text("Soft heart. Strong discipline. Powerful code. 💗", size=18, text_align=ft.TextAlign.CENTER)
    )

ft.app(target=main)
