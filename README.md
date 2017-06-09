{
   "workbench.iconTheme": "vscode-icons",

    //头文件注释

    "psi-header.config": {

        "forceToTop": true,

        "blankLinesAfter": 0,

        "license": "Custom"

    },

    "psi-header.changes-tracking": {

        "isActive": true,

        "modAuthor": "Modified By: ",

        "modDate": "Last Modified: ",

        "modDateFormat": "date",

        "include": [],

        "exclude": [

            "markdown",

            "json"

        ]

    },

    "psi-header.license-text": [

"============================================================================",

"This file (and its contents) are the intellectual property of Omni Remotes LLC.",

"It may not be used, copied, distributed or otherwise  disclosed in whole or in",

"part without the express written permission of Omni Remotes, LLC.",

"============================================================================",

 

    ],

    "psi-header.variables": [

        ["company", "Home Control (suzhou) Limtd"],

        ["author", "shifeng.lu"],

        ["authoremail", "shifeng.lu@omniremotes.com"],


    ],

    "psi-header.lang-config": [

        {

        "language": "python",

            "begin": "###",

            "prefix": "# ",

            "end": "###",

            "blankLinesAfter": 0,

            "beforeHeader": [

                "#!/usr/bin/env python3",

                "# -*- coding:utf-8 -*-"

            ]

        },

         {

            "language": "C",

            "begin": "/**",

            "prefix": " * ",

            "end": " */",

            "blankLinesAfter": 2,

            "forceToTop": false

        }, 

    ],

    "psi-header.templates": [

         {

            "language": "*",

            "template": [

                "<<licensetext>>",

                "       ___                           _    File: <<filename>>",

                "     .'   `.                        (_)   Created Date: <<date>>",

                "    /  .-.  ` _ .--..--.   _ .--.   __    Author: <<author>>",

                "    | |   | |[ `.-. .-. | [ `.-. | [  |   -----",

                "    `  `-'  / | | | | | |  | | | |  | |   Last Modified: <<date>>",

                "     `.___.' [___||__||__][___||__][___]  Modified By: <<modAuthor>>",

                "                                          -----",

                "============================================================================",

                "Copyright (c) <<year>> <<company>>" ,

                "============================================================================",

              

            ]

        },

       

        

    ]

}
