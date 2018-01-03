Program 2017
############

:slug: program2017
:summary: Program 2017

Program 2017
============

It's been a difficult task to create a program, considering we received 38
proposals and time only allows for a maximum of 9 slots. Many promising
proposals had to be left out to our regret, but we are certain that we managed
to put together an amazing and very diverse program!

.. raw:: html

    <table id="program" class="table-hover table-striped">
        <thead>
            <tr>
                <th class="col-time">Time</th>
                <th class="col-content">Content</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>08:15 – 09:00</td>
                <td class="meta">Registration + Coffee (open until 09:15)</td>
            </tr>
            <tr>
                <td>09:00 – 09:15</td>
                <td class="meta">Welcome</td>
            </tr>
            <tr>
                <td>09:15 – 10:00</td>
                <td>
                    Gaël Varoquaux<br>
                    <a href="#">Writing Code for Science and Data</a>
                    <p class="description">
                        Scientific research or data science need rapid experimentation and
                        building intuitions from data. Yet, in academia or in the industry, the
                        code must live on to be useful for future enquiries or in production.
                        Always experimenting yet writing production-ready robust code may seem a
                        conundrum. However it shares a lot with agile or extreme programming
                        techniques. It is an interesting test bed of programming practices.
                        <br>
                        I will explore simple, and less simple, practices that I have encountered
                        in my research for fast turn around and consolidation of code. I will
                        discuss how these considerations led to the design of scikit-learn, that
                        enables easy machine learning, yet is used in production. Finally, I will
                        mention some scikit-learn gems, new or forgotten.
                    </p>
                </td>
            </tr>
            <tr>
                <td>10:00 - 10:30</td>
                <td>
                    Radomir Dopieralski<br>
                    <a href="#">Hobby Electronics with MicroPython</a>
                    <p class="description">
                        A gentle introduction into the world of hobby electronics. Robots, art, gadgets, monitoring, tools, toys, home appliances, wearables -- with microcontrollers you can make anything. And now, that MicroPython is here, you can easily learn to program them.
                    </p>
                </td>
            </tr>
            <tr>
                <td>10:30 - 11:00</td>
                <td class="meta">Coffee break</td>
            </tr>
            <tr>
                <td>11:00 – 11:40</td>
                <td>
                    Armin Rigo<br>
                    <a href="#">RevDB, a Reverse Debugger</a>
                    <p class="description">
                        RevDB is an experimental "reverse debugger" for Python, similar to UndoDB-GDB or LL for C. You run your program once, in "record" mode, producing a log file; once you get buggy behavior, you start the reverse-debugger on the log file. It gives an (improved) pdb-like experience, but it is replaying your program exactly as it ran---all input/outputs are replayed from the log file instead of being redone.
                        <br><br>
                        The main point is that you can then go backward as well as forward in time: from a situation that looks really buggy you can go back and discover how it came to be. You also get "watchpoints", which are very useful to find when things change. Watchpoints work both forward and backward.
                        <br><br>
                        I will show on small examples how you can use it, and also give an idea about how it works. It is based on PyPy, not CPython, so you need to ensure your program works on PyPy in the first place (but chances are that it does).
                    </p>
                </td>
            </tr>
            <tr>
                <td>11:40 – 12:10</td>
                <td>
                    Barnaby Skinner<br>
                    <a href="#">Scraping the Federal Administrative Court's Database and Analysing the Verdicts </a>
                    <p class="description">
                        For years, lawyers and attorneys working in Switzerland have sensed that cases of migrants appealing deportation weren't treated equally by the 24 judges of the Swiss Federal Administrative Court.
                        <br><br>
                        To explore this claim we scraped the 30'000 verdicts of the court since 2007 from the court's data base. Then used the Python libraries pandas, glob and regular expressions to explore the data.
                    </p>
                </td>
            </tr>
            <tr>
                <td>12:10 – 12:40</td>
                <td>
                    Dave Halter<br>
                    <a href="#">Python is Weird</a>
                    <p class="description">
                        A lot of people think that Python is a really simple and straightforward language. Python hides a lot of peculiarities very well, but for the sake of this talk we will try to uncover them.
                        <br><br>
                        I will be explaining how the whole process of tokenizing -> parsing -> ast creation -> bytecode works and will use odd Python code to show the internals. Do you think `++4;` is valid Python? Or how about `0jif.1else-2`? There's no spaces in it. Go figure! "Edge cases" will help us understand the inner workings of Python.
                        <br><br>
                        We will be looking into how modules, classes and instances are really just fancy dictionaries and how importing is really nothing else than storing a module into a dictionary (`sys.modules`).
                        <br><br>
                        There's a lot of things we can learn from diving deep into the details of our beloved languages.
                    </p>
                </td>
            </tr>
            <tr>
                <td>12:40 – 14:00</td>
                <td class="meta">Lunch</td>
            </tr>
            <tr>
                <td>14:00 – 14:30</td>
                <td>
                    Dan Maas<br>
                    <a href="#">Massively Multiplayer Online Game Servers in Twisted Python</a>
                    <p class="description">
                        How we designed and built back-end servers for MMO games on the web like Thunder Run (www.thunderrun.com), using Python to handle 100,000+ monthly players. How to take advantage of the Twisted library and asynchronous I/O for low-latency networking.
                    </p>
                </td>
            </tr>
            <tr>
                <td>14:30 – 15:00</td>
                <td>
                    Aarno Aukia<br>
                    <a href="#">Scalable Python with Docker, Kubernetes and Openshift</a>
                    <p class="description">
                        New technologies like Docker, Kubernetes and Openshift make it much easier to run python applications on multiple servers for redundancy and load-balancing. In this talk I will explain how the 100% open-source Docker, Kubernetes and Openshift work and how to run python applications on this stack. I will show two or more live examples how to combine them with Git into a complete continuous delivery pipeline.
                    </p>
                </td>
            </tr>
            <tr>
                <td>15:00 – 15:45</td>
                <td class="meta">Coffee break</td>
            </tr>
            <tr>
                <td>15:45 – 16:15</td>
                <td>
                    Rae Knowler<br>
                    <a href="#">Python, Locales and Writing Systems</a>
                    <p class="description">
                        Python 3 removes a lot of the confusion around Unicode handling in Python, but that by no means fixes everything. Different locales and writing systems have unique behaviours that can trip you up. Here's some of the worst ones and how to handle them correctly.
                    </p>
                </td>
            </tr>
            <tr>
                <td>16:15 – 16:45</td>
                <td>
                    Raphael Nestler<br>
                    <a href="#">Python in the Hardware Industry</a>
                    <p class="description">
                        This talk will be about the usage of Python inside of Sensirion, a hardware company producing sensors. We will see where and how we rely on Python and how the usage evolved from collections of small Python scripts in each department to a stack of gerrit, Jenkins and devpi to develop, test and deploy Python packages to 100+ non software engineers in the lab.
                    </p>
                </td>
            </tr>
            <tr>
                <td>16:45 – 17:00</td>
                <td class="meta">Closing</td>
            </tr>
            <tr>
                <td>17:00 – 20:00</td>
                <td>Social Event / Apéro</td>
            </tr>
        </tbody>
    </table>

    <script type="text/javascript" src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
    <script type="text/javascript">
        $(document).ready(function() {
            $('table#program .description').hide();
            $('table#program a').click(function() {
                $(this).siblings('.description').toggle('fast');
                return false;
            });
        });
    </script>

Aperitif
========

Right after the conference we'll have a small aperitif at HSR's cafeteria,
sponsored by `4teamwork <https://www.4teamwork.ch/>`_. There will be soft drinks,
water, beer and sandwiches free of charge for all conference attendees.
