<!-- Vue component -->
<template>
    <div>
        <treeselect :options="options"
                    :value="value"
                    :normalizer="normalizer" />
    </div>
</template>

<script>
    
    import Treeselect from '@riophae/vue-treeselect'
    // import the styles
    import '@riophae/vue-treeselect/dist/vue-treeselect.css';
    
   

    export default {
        components: { Treeselect },
        data: () => ({
            value: null,
            options: [
                {
                    "key": "pk",
                    "name": "Pakistan",
                    "subOptions": [
                        {
                            "key": "pj",
                            "name": "Punjab",
                            "subOptions": [
                                {
                                    "key": "Attock",
                                    "name": "Attock",
                                    "subOptions": [
                                        {
                                            "key": "Attock",
                                            "name": "Attock"
                                        },
                                        {
                                            "key": "FatehJang",
                                            "name": "Fateh Jang"
                                        },
                                        {
                                            "key": "HassanAbdal",
                                            "name": "Hassan Abdal"
                                        },
                                        {
                                            "key": "Hazro",
                                            "name": "Hazro "
                                        },
                                        {
                                            "key": "PindiGheb",
                                            "name": "Pindi Gheb"
                                        }
                                    ]
                                },
                                {
                                    "key": "Bahawalnagar",
                                    "name": "Bahawalnagar",
                                    "subOptions": [
                                        {
                                            "key": "Bahawalnagar",
                                            "name": "Bahawalnagar"
                                        },
                                        {
                                            "key": "Chishtian",
                                            "name": "Chishtian"
                                        },
                                        {
                                            "key": "FortAbbas",
                                            "name": "Fort Abbas"
                                        },
                                        {
                                            "key": "Haroonabad",
                                            "name": "Haroonabad "
                                        },
                                        {
                                            "key": "Minchinabad",
                                            "name": "Minchinabad "
                                        }
                                    ]
                                },
                                {
                                    "key": "Bahawalpur",
                                    "name": "Bahawalpur",
                                    "subOptions": [
                                        {
                                            "key": "AhmadpurEast",
                                            "name": "Ahmadpur East"
                                        },
                                        {
                                            "key": "BahawalpurCity",
                                            "name": "Bahawalpur City"
                                        },
                                        {
                                            "key": "BahawalpurSaddar",
                                            "name": "Bahawalpur Saddar"
                                        },
                                        {
                                            "key": "Hasilpur",
                                            "name": "Hasilpur "
                                        },
                                        {
                                            "key": "KhairpurTamewali",
                                            "name": "Khairpur Tamewali "
                                        },
                                        {
                                            "key": "Yazman",
                                            "name": "Yazman  "
                                        }
                                    ]
                                },
                                {
                                    "key": "Bhakkar",
                                    "name": "Bhakkar",
                                    "subOptions": [
                                        {
                                            "key": "Bhakkar",
                                            "name": "Bhakkar "
                                        },
                                        {
                                            "key": "DaryaKhan",
                                            "name": "Darya Khan"
                                        },
                                        {
                                            "key": "KalurKot",
                                            "name": "Kalur Kot "
                                        },
                                        {
                                            "key": "Mankera",
                                            "name": "Mankera "
                                        }
                                    ]
                                },
                                {
                                    "key": "Chakwal",
                                    "name": "Chakwal",
                                    "subOptions": [
                                        {
                                            "key": "Chakwal",
                                            "name": "Chakwal "
                                        },
                                        {
                                            "key": "ChoaSaidanShah",
                                            "name": "Choa Saidan Shah "
                                        },
                                        {
                                            "key": "KallarKahar",
                                            "name": "Kallar Kahar  "
                                        },
                                        {
                                            "key": "Lawa",
                                            "name": "Lawa "
                                        },
                                        {
                                            "key": "Talagang",
                                            "name": "Talagang "
                                        }
                                    ]
                                },
                                {
                                    "key": "Chiniot",
                                    "name": "Chiniot",
                                    "subOptions": [
                                        {
                                            "key": "Bhawana",
                                            "name": "Bhawana "
                                        },
                                        {
                                            "key": "Chiniot",
                                            "name": "Chiniot "
                                        },
                                        {
                                            "key": "Lalian",
                                            "name": "Lalian   "
                                        }
                                    ]
                                },
                                {
                                    "key": "DeraGhaziKhan",
                                    "name": "Dera Ghazi Khan",
                                    "subOptions": [
                                        {
                                            "key": "FortMunro",
                                            "name": "Fort Munro "
                                        },
                                        {
                                            "key": "DeraGhaziKhan",
                                            "name": "Dera Ghazi Khan "
                                        },
                                        {
                                            "key": "KotChutta",
                                            "name": "Kot Chutta  "
                                        },
                                        {
                                            "key": "Taunsa",
                                            "name": "Taunsa  "
                                        }
                                    ]
                                },
                                {
                                    "key": "Faisalabad",
                                    "name": "Faisalabad",
                                    "subOptions": [
                                        {
                                            "key": "ChakJhumra",
                                            "name": "Chak Jhumra "
                                        },
                                        {
                                            "key": "FaisalabadCity",
                                            "name": "Faisalabad City "
                                        },
                                        {
                                            "key": "FaisalabadSaddar",
                                            "name": "Faisalabad Saddar  "
                                        },
                                        {
                                            "key": "Jaranwala",
                                            "name": "Jaranwala  "
                                        },
                                        {
                                            "key": "Samundri",
                                            "name": "Samundri  "
                                        },
                                        {
                                            "key": "Tandlianwala",
                                            "name": "Tandlianwala  "
                                        }
                                    ]
                                },
                                {
                                    "key": "Gujranwala",
                                    "name": "Gujranwala",
                                    "subOptions": [
                                        {
                                            "key": "GujranwalaCity",
                                            "name": "Gujranwala City  "
                                        },
                                        {
                                            "key": "GujranwalaSaddar",
                                            "name": "Gujranwala Saddar  "
                                        },
                                        {
                                            "key": "Kamoki",
                                            "name": "Kamoki   "
                                        },
                                        {
                                            "key": "Nowshera",
                                            "name": "Nowshera  "
                                        },
                                        {
                                            "key": "Wazirabad",
                                            "name": "Wazirabad  "
                                        }
                                    ]
                                },
                                {
                                    "key": "Gujrat",
                                    "name": "Gujrat",
                                    "subOptions": [
                                        {
                                            "key": "Gujrat",
                                            "name": "Gujrat   "
                                        },
                                        {
                                            "key": "Kharian",
                                            "name": "Kharian   "
                                        },
                                        {
                                            "key": "SaraiAlamgir",
                                            "name": "Sarai Alamgir   "
                                        }
                                    ]
                                },
                                {
                                    "key": "Hafizabad",
                                    "name": "Hafizabad",
                                    "subOptions": [
                                        {
                                            "key": "Hafizabad",
                                            "name": "Hafizabad   "
                                        },
                                        {
                                            "key": "PindiBhattian",
                                            "name": "Pindi Bhattian   "
                                        }
                                    ]
                                },
                                {
                                    "key": "Jhang",
                                    "name": "Jhang",
                                    "subOptions": [
                                        {
                                            "key": "18 Hazari",
                                            "name": "18 Hazari   "
                                        },
                                        {
                                            "key": "AhmadpurSial",
                                            "name": "Ahmadpur Sial    "
                                        },
                                        {
                                            "key": "Jhang",
                                            "name": "Jhang     "
                                        },
                                        {
                                            "key": "Shorkot",
                                            "name": "Shorkot     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Jhelum",
                                    "name": "Jhelum",
                                    "subOptions": [
                                        {
                                            "key": " Dina",
                                            "name": " Dina   "
                                        },
                                        {
                                            "key": "Jhelum",
                                            "name": "Jhelum     "
                                        },
                                        {
                                            "key": "PindDadanKhan",
                                            "name": "Pind Dadan Khan     "
                                        },
                                        {
                                            "key": "Sohawa",
                                            "name": "Sohawa     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kasur",
                                    "name": "Kasur",
                                    "subOptions": [
                                        {
                                            "key": " Chunian",
                                            "name": " Chunian   "
                                        },
                                        {
                                            "key": "Kasur",
                                            "name": "Kasur     "
                                        },
                                        {
                                            "key": "Kot Radha Kishan",
                                            "name": "Kot Radha Kishan     "
                                        },
                                        {
                                            "key": "Pattoki",
                                            "name": "Pattoki     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Khanewal",
                                    "name": "Khanewal",
                                    "subOptions": [
                                        {
                                            "key": " Jehanian",
                                            "name": " Jehanian   "
                                        },
                                        {
                                            "key": "Kabirwala",
                                            "name": "Kabirwala     "
                                        },
                                        {
                                            "key": "Khanewal",
                                            "name": "Khanewal     "
                                        },
                                        {
                                            "key": "MianChannu",
                                            "name": "Mian Channu     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Khushab",
                                    "name": "Khushab",
                                    "subOptions": [
                                        {
                                            "key": " Khushab",
                                            "name": " Khushab   "
                                        },
                                        {
                                            "key": "Nowshera",
                                            "name": "Nowshera     "
                                        },
                                        {
                                            "key": "Nurpur",
                                            "name": "Nurpur     "
                                        },
                                        {
                                            "key": "Quaidabad",
                                            "name": "Quaidabad      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Lahore",
                                    "name": "Lahore",
                                    "subOptions": [
                                        {
                                            "key": " LahoreCantonment",
                                            "name": " Lahore Cantonment   "
                                        },
                                        {
                                            "key": "LahoreCity",
                                            "name": "Lahore City     "
                                        },
                                        {
                                            "key": "ModelTown",
                                            "name": "Model Town     "
                                        },
                                        {
                                            "key": "Riawand",
                                            "name": "Riawand      "
                                        },
                                        {
                                            "key": "Shalimar",
                                            "name": "Shalimar      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Layyah",
                                    "name": "Layyah",
                                    "subOptions": [
                                        {
                                            "key": " Chaubara",
                                            "name": " Chaubara    "
                                        },
                                        {
                                            "key": "KarorLalEsan",
                                            "name": "Karor Lal Esan      "
                                        },
                                        {
                                            "key": "Layyah",
                                            "name": "Layyah      "
                                        }
                                    ]
                                },
                                {
                                    "key": "MandiBahauddin",
                                    "name": "Mandi Bahauddin",
                                    "subOptions": [
                                        {
                                            "key": " Malakwal",
                                            "name": " Malakwal    "
                                        },
                                        {
                                            "key": "MandiBahauddin",
                                            "name": "Mandi Bahauddin     "
                                        },
                                        {
                                            "key": "Phalia",
                                            "name": "Phalia      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Mianwali",
                                    "name": "Mianwali",
                                    "subOptions": [
                                        {
                                            "key": " Isakhel",
                                            "name": " Isakhel    "
                                        },
                                        {
                                            "key": "Mianwali",
                                            "name": "Mianwali      "
                                        },
                                        {
                                            "key": "Piplan",
                                            "name": "Piplan      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Multan",
                                    "name": "Multan",
                                    "subOptions": [
                                        {
                                            "key": " Jalalpur Pirwala",
                                            "name": " Jalalpur Pirwala    "
                                        },
                                        {
                                            "key": "Multan",
                                            "name": "Multan       "
                                        },
                                        {
                                            "key": "Shujabad",
                                            "name": "Shujabad      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Muzaffargarh",
                                    "name": "Muzaffargarh",
                                    "subOptions": [
                                        {
                                            "key": " Alipur",
                                            "name": " Alipur    "
                                        },
                                        {
                                            "key": "Jatoi",
                                            "name": "Jatoi      "
                                        },
                                        {
                                            "key": "Kot Addu",
                                            "name": "Kot Addu      "
                                        },
                                        {
                                            "key": "Muzaffargarh ",
                                            "name": "Muzaffargarh       "
                                        }
                                    ]
                                },
                                {
                                    "key": "NankanaSahib",
                                    "name": "Nankana Sahib",
                                    "subOptions": [
                                        {
                                            "key": " Nankana Sahib",
                                            "name": " Nankana Sahib    "
                                        },
                                        {
                                            "key": "Sangla Hill",
                                            "name": "Sangla Hill      "
                                        },
                                        {
                                            "key": "Shahkot",
                                            "name": "Shahkot      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Narowal",
                                    "name": "Narowal",
                                    "subOptions": [
                                        {
                                            "key": " Narowal",
                                            "name": " Narowal    "
                                        },
                                        {
                                            "key": "Shakargarh",
                                            "name": "Shakargarh      "
                                        },
                                        {
                                            "key": "Zafarwal",
                                            "name": "Zafarwal      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Okara",
                                    "name": "Okara",
                                    "subOptions": [
                                        {
                                            "key": " Depalpur",
                                            "name": " Depalpur    "
                                        },
                                        {
                                            "key": "Okara",
                                            "name": "Okara     "
                                        },
                                        {
                                            "key": "Renala Khurd",
                                            "name": "Renala Khurd      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Pakpattan",
                                    "name": "Pakpattan",
                                    "subOptions": [
                                        {
                                            "key": " Arifwala",
                                            "name": " Arifwala    "
                                        },
                                        {
                                            "key": "Pakpattan",
                                            "name": "Pakpattan     "
                                        }
                                    ]
                                },
                                {
                                    "key": "RahimYarKhan",
                                    "name": "Rahim Yar Khan",
                                    "subOptions": [
                                        {
                                            "key": " Khanpur",
                                            "name": " Khanpur    "
                                        },
                                        {
                                            "key": "Liaquatpur",
                                            "name": "Liaquatpur     "
                                        },
                                        {
                                            "key": "Rahim Yar Khan",
                                            "name": "Rahim Yar Khan     "
                                        },
                                        {
                                            "key": "Sadiqabad",
                                            "name": "Sadiqabad     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Rajanpur",
                                    "name": "Rajanpur",
                                    "subOptions": [
                                        {
                                            "key": " Jampur",
                                            "name": " Jampur    "
                                        },
                                        {
                                            "key": "Rajanpur",
                                            "name": "Rajanpur     "
                                        },
                                        {
                                            "key": "Rojhan ",
                                            "name": "Rojhan      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Rawalpindi",
                                    "name": "Rawalpindi",
                                    "subOptions": [
                                        {
                                            "key": " Gujar Khan",
                                            "name": " Gujar Khan    "
                                        },
                                        {
                                            "key": "Kahuta",
                                            "name": "Kahuta     "
                                        },
                                        {
                                            "key": "Kallar Sayyedan",
                                            "name": "Kallar Sayyedan     "
                                        },
                                        {
                                            "key": "Kotli Sattian",
                                            "name": "Kotli Sattian     "
                                        },
                                        {
                                            "key": "Murree ",
                                            "name": "Murree     "
                                        },
                                        {
                                            "key": "Rawalpindi ",
                                            "name": "Rawalpindi     "
                                        },
                                        {
                                            "key": "Taxila ",
                                            "name": "Taxila      "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sahiwal",
                                    "name": "Sahiwal",
                                    "subOptions": [
                                        {
                                            "key": " Chichawatni",
                                            "name": " Chichawatni    "
                                        },
                                        {
                                            "key": "Sahiwal",
                                            "name": "Sahiwal     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sargodha",
                                    "name": "Sargodha",
                                    "subOptions": [
                                        {
                                            "key": " Bhalwal",
                                            "name": " Bhalwal    "
                                        },
                                        {
                                            "key": "Bhera",
                                            "name": "Bhera     "
                                        },
                                        {
                                            "key": "Kot Momin",
                                            "name": "Kot Momin     "
                                        },
                                        {
                                            "key": "Sargodha",
                                            "name": "Sargodha     "
                                        },
                                        {
                                            "key": "Shahpur",
                                            "name": "Shahpur     "
                                        },
                                        {
                                            "key": "Sillanwali",
                                            "name": "Sillanwali     "
                                        },
                                        {
                                            "key": "Sahiwal",
                                            "name": "Sahiwal     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sheikhupura",
                                    "name": "Sheikhupura",
                                    "subOptions": [
                                        {
                                            "key": " Ferozewala",
                                            "name": " Ferozewala    "
                                        },
                                        {
                                            "key": "Muridke",
                                            "name": "Muridke     "
                                        },
                                        {
                                            "key": "Safdarabad ",
                                            "name": "Safdarabad     "
                                        },
                                        {
                                            "key": "Sharkpur",
                                            "name": "Sharkpur     "
                                        },
                                        {
                                            "key": "Sheikhupura",
                                            "name": "Sheikhupura     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sialkot",
                                    "name": "Sialkot",
                                    "subOptions": [
                                        {
                                            "key": " Daska",
                                            "name": " Daska    "
                                        },
                                        {
                                            "key": "Pasrur",
                                            "name": "Pasrur     "
                                        },
                                        {
                                            "key": "Sambrial ",
                                            "name": "Sambrial     "
                                        },
                                        {
                                            "key": "Sialkot",
                                            "name": "Sialkot     "
                                        }
                                    ]
                                },
                                {
                                    "key": "TobaTekSingh",
                                    "name": "Toba Tek Singh",
                                    "subOptions": [
                                        {
                                            "key": " Gojra",
                                            "name": " Gojra    "
                                        },
                                        {
                                            "key": "Kamalia",
                                            "name": "Kamalia     "
                                        },
                                        {
                                            "key": "Pir Mahal ",
                                            "name": "Pir Mahal    "
                                        },
                                        {
                                            "key": "Toba Tek Singh",
                                            "name": "Toba Tek Singh     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Vehari",
                                    "name": "Vehari",
                                    "subOptions": [
                                        {
                                            "key": " Burewala",
                                            "name": " Burewala    "
                                        },
                                        {
                                            "key": "Mailsi",
                                            "name": "Mailsi     "
                                        },
                                        {
                                            "key": "Vehari ",
                                            "name": "Vehari     "
                                        }
                                    ]
                                }
                            ]
                        },
                        {
                            "key": "balochistan",
                            "name": "Balochistan",
                            "subOptions": [
                                {
                                    "key": "Awaran",
                                    "name": "Awaran",
                                    "subOptions": [
                                        {
                                            "key": " Awaran",
                                            "name": " Awaran    "
                                        },
                                        {
                                            "key": "Gishkore",
                                            "name": "Gishkore     "
                                        },
                                        {
                                            "key": "Jhal Jao ",
                                            "name": "Jhal Jao     "
                                        },
                                        {
                                            "key": "Mashkai",
                                            "name": "Mashkai     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Barkhan",
                                    "name": "Barkhan",
                                    "subOptions": [
                                        {
                                            "key": " Barkhan",
                                            "name": " Barkhan    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Chagi",
                                    "name": "Chagi",
                                    "subOptions": [
                                        {
                                            "key": " Chagai",
                                            "name": " Chagai    "
                                        },
                                        {
                                            "key": "Dalbandin",
                                            "name": "Dalbandin     "
                                        },
                                        {
                                            "key": "Nokundi Sub ",
                                            "name": "Nokundi Sub     "
                                        },
                                        {
                                            "key": "Taftan Sub",
                                            "name": "Taftan Sub     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Derabugti",
                                    "name": "Dera Bugti",
                                    "subOptions": [
                                        {
                                            "key": " Baiker",
                                            "name": " Baiker    "
                                        },
                                        {
                                            "key": "Dera Bugti",
                                            "name": "Dera Bugti     "
                                        },
                                        {
                                            "key": "Loti ",
                                            "name": "Loti     "
                                        },
                                        {
                                            "key": "Phelawagh",
                                            "name": "Phelawagh     "
                                        },
                                        {
                                            "key": "Pir Koh Sub",
                                            "name": "Pir Koh Sub     "
                                        },
                                        {
                                            "key": "Sangsillah",
                                            "name": "Sangsillah     "
                                        },
                                        {
                                            "key": "Sui",
                                            "name": "Sui     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Gawadar",
                                    "name": "Gawadar",
                                    "subOptions": [
                                        {
                                            "key": " Gwadar",
                                            "name": " Gwadar    "
                                        },
                                        {
                                            "key": "Jiwani",
                                            "name": "Jiwani     "
                                        },
                                        {
                                            "key": "Ormara ",
                                            "name": "Ormara     "
                                        },
                                        {
                                            "key": "Pasni",
                                            "name": "Pasni     "
                                        },
                                        {
                                            "key": "Suntsar",
                                            "name": "Suntsar     "
                                        }
                                    ]
                                },
                                {
                                    "key": "harnai",
                                    "name": "harnai",
                                    "subOptions": [
                                        {
                                            "key": " Harnai",
                                            "name": " Harnai    "
                                        },
                                        {
                                            "key": "Khoast",
                                            "name": "Khoast     "
                                        },
                                        {
                                            "key": "Shahrig ",
                                            "name": "Shahrig     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Jaffarabad",
                                    "name": "Jaffarabad",
                                    "subOptions": [
                                        {
                                            "key": " Gandhaka",
                                            "name": " Gandhaka    "
                                        },
                                        {
                                            "key": "Jhat Pat",
                                            "name": "Jhat Pat     "
                                        },
                                        {
                                            "key": "Usta Muhammad ",
                                            "name": "Usta Muhammad     "
                                        }
                                    ]
                                },
                                {
                                    "key": "JhalMagsi",
                                    "name": "Jhal Magsi",
                                    "subOptions": [
                                        {
                                            "key": " Gandawa",
                                            "name": " Gandawa    "
                                        },
                                        {
                                            "key": "Jhal Magsi",
                                            "name": "Jhal Magsi     "
                                        },
                                        {
                                            "key": "Mirpur ",
                                            "name": "Mirpur     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kachhi",
                                    "name": "Kachhi (Bolan)",
                                    "subOptions": [
                                        {
                                            "key": " Balanari",
                                            "name": " Balanari    "
                                        },
                                        {
                                            "key": "Dhadar",
                                            "name": "Dhadar     "
                                        },
                                        {
                                            "key": "Khattan ",
                                            "name": "Khattan     "
                                        },
                                        {
                                            "key": "Mach",
                                            "name": "Mach     "
                                        },
                                        {
                                            "key": "Sanni",
                                            "name": "Sanni     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kalat",
                                    "name": "Kalat",
                                    "subOptions": [
                                        {
                                            "key": " Gazg",
                                            "name": " Gazg    "
                                        },
                                        {
                                            "key": "Johan",
                                            "name": "Johan     "
                                        },
                                        {
                                            "key": "Kalat ",
                                            "name": "Kalat     "
                                        },
                                        {
                                            "key": "Mangochar",
                                            "name": "Mangochar     "
                                        },
                                        {
                                            "key": "Surab",
                                            "name": "Surab     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kech",
                                    "name": "Kech",
                                    "subOptions": [
                                        {
                                            "key": " Balnigor",
                                            "name": " Balnigor    "
                                        },
                                        {
                                            "key": "Buleda",
                                            "name": "Buleda     "
                                        },
                                        {
                                            "key": "Dasht ",
                                            "name": "Dasht     "
                                        },
                                        {
                                            "key": "Hoshab",
                                            "name": "Hoshab     "
                                        },
                                        {
                                            "key": "Kech",
                                            "name": "Kech     "
                                        },
                                        {
                                            "key": "Mand",
                                            "name": "Mand     "
                                        },
                                        {
                                            "key": "Tump",
                                            "name": "Tump     "
                                        },
                                        {
                                            "key": "Zamuran",
                                            "name": "Zamuran     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kharan",
                                    "name": "Kharan",
                                    "subOptions": [
                                        {
                                            "key": " Kharan",
                                            "name": " Kharan    "
                                        },
                                        {
                                            "key": "Tohumulk",
                                            "name": "Tohumulk     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Khuzdar",
                                    "name": "Khuzdar",
                                    "subOptions": [
                                        {
                                            "key": " Aranji",
                                            "name": " Aranji    "
                                        },
                                        {
                                            "key": "Karakh",
                                            "name": "Karakh     "
                                        },
                                        {
                                            "key": "Khuzdar ",
                                            "name": "Khuzdar     "
                                        },
                                        {
                                            "key": "Moola",
                                            "name": "Moola     "
                                        },
                                        {
                                            "key": "Nal Sub",
                                            "name": "Nal Sub     "
                                        },
                                        {
                                            "key": "Ornach",
                                            "name": "Ornach     "
                                        },
                                        {
                                            "key": "Saroona",
                                            "name": "Saroona     "
                                        },
                                        {
                                            "key": "Wadh",
                                            "name": "Wadh     "
                                        },
                                        {
                                            "key": "Zehri",
                                            "name": "Zehri     "
                                        },
                                        {
                                            "key": "Bara",
                                            "name": "Bara     "
                                        },
                                        {
                                            "key": "Jamrud",
                                            "name": "Jamrud     "
                                        },
                                        {
                                            "key": "Landi Kotal",
                                            "name": "Landi Kotal     "
                                        },
                                        {
                                            "key": "Mula Ghori",
                                            "name": "Mula Ghori     "
                                        }
                                    ]
                                },
                                {
                                    "key": "KillaAbdullah",
                                    "name": "Killa Abdullah",
                                    "subOptions": [
                                        {
                                            "key": " Chaman",
                                            "name": " Chaman    "
                                        },
                                        {
                                            "key": "Dobandi",
                                            "name": "Dobandi     "
                                        },
                                        {
                                            "key": "Killa Abdullah ",
                                            "name": "Killa Abdullah     "
                                        },
                                        {
                                            "key": "Gulistan",
                                            "name": "Gulistan     "
                                        }
                                    ]
                                },
                                {
                                    "key": "KillaSaifullah",
                                    "name": "Killa Saifullah",
                                    "subOptions": [
                                        {
                                            "key": " Baddini",
                                            "name": " Baddini    "
                                        },
                                        {
                                            "key": "Kan Mehtarzai",
                                            "name": "Kan Mehtarzai     "
                                        },
                                        {
                                            "key": "Killa Saifullah ",
                                            "name": "Killa Saifullah     "
                                        },
                                        {
                                            "key": "Loiband",
                                            "name": "Loiband     "
                                        },
                                        {
                                            "key": "Muslim Bagh",
                                            "name": "Muslim Bagh     "
                                        },
                                        {
                                            "key": "Shinki Sub ",
                                            "name": "Shink iSub     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kohlu",
                                    "name": "Kohlu",
                                    "subOptions": [
                                        {
                                            "key": " Grisani",
                                            "name": " Grisani    "
                                        },
                                        {
                                            "key": "Kahan",
                                            "name": "Kahan     "
                                        },
                                        {
                                            "key": "Kohlu ",
                                            "name": "Kohlu     "
                                        },
                                        {
                                            "key": "Mawand",
                                            "name": "Mawand     "
                                        },
                                        {
                                            "key": "Tamboo",
                                            "name": "Tamboo     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Lasbela",
                                    "name": "Lasbela",
                                    "subOptions": [
                                        {
                                            "key": " Bela",
                                            "name": " Bela    "
                                        },
                                        {
                                            "key": "Dureji",
                                            "name": "Dureji     "
                                        },
                                        {
                                            "key": "Gadani ",
                                            "name": "Gadani     "
                                        },
                                        {
                                            "key": "Hub",
                                            "name": "Hub     "
                                        },
                                        {
                                            "key": "Lakhra",
                                            "name": "Lakhra     "
                                        },
                                        {
                                            "key": "Liari",
                                            "name": "Liari     "
                                        },
                                        {
                                            "key": "Sonmiani/Winder",
                                            "name": "Sonmiani/Winder     "
                                        },
                                        {
                                            "key": "Uthal",
                                            "name": "Uthal     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Lehri",
                                    "name": "Lehri",
                                    "subOptions": [
                                        {
                                            "key": " Bhag",
                                            "name": " Bhag    "
                                        },
                                        {
                                            "key": "Lehri",
                                            "name": "Lehri     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Loralai",
                                    "name": "Loralai",
                                    "subOptions": [
                                        {
                                            "key": " Bori",
                                            "name": " Bori    "
                                        },
                                        {
                                            "key": "Duki",
                                            "name": "Duki     "
                                        },
                                        {
                                            "key": "Loralai ",
                                            "name": "Loralai     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Mastung",
                                    "name": "Mastung",
                                    "subOptions": [
                                        {
                                            "key": " Dasht",
                                            "name": " Dasht    "
                                        },
                                        {
                                            "key": "Khad Koocha",
                                            "name": "Khad Koocha     "
                                        },
                                        {
                                            "key": "Kirdgap ",
                                            "name": "Kirdgap     "
                                        },
                                        {
                                            "key": "Mastung",
                                            "name": "Mastung     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Musakhel",
                                    "name": "Musakhel",
                                    "subOptions": [
                                        {
                                            "key": " Drug",
                                            "name": " Drug    "
                                        },
                                        {
                                            "key": "Kingri",
                                            "name": "Kingri     "
                                        },
                                        {
                                            "key": "Musakhel ",
                                            "name": "Musakhel     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Nasirabad",
                                    "name": "Nasirabad"
                                },
                                {
                                    "key": "Nasirabad",
                                    "name": "Nasirabad"
                                },
                                {
                                    "key": "Nushki",
                                    "name": "Nushki",
                                    "subOptions": [
                                        {
                                            "key": " Nushki",
                                            "name": " Nushki    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Pishin",
                                    "name": "Pishin",
                                    "subOptions": [
                                        {
                                            "key": " Barshore",
                                            "name": " Barshore    "
                                        },
                                        {
                                            "key": "Hurramzai",
                                            "name": "Hurramzai     "
                                        },
                                        {
                                            "key": "Karezat ",
                                            "name": "Karezat     "
                                        },
                                        {
                                            "key": "Pishin",
                                            "name": "Pishin     "
                                        },
                                        {
                                            "key": "Saranan",
                                            "name": "Saranan     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Quetta",
                                    "name": "Quetta",
                                    "subOptions": [
                                        {
                                            "key": " Panj Pai",
                                            "name": " Panj Pai    "
                                        },
                                        {
                                            "key": "Quetta",
                                            "name": "Quetta     "
                                        },
                                        {
                                            "key": "Quetta Sadar ",
                                            "name": "Quetta Sadar     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sheerani",
                                    "name": "Sheerani",
                                    "subOptions": [
                                        {
                                            "key": " Sheerani",
                                            "name": " Sheerani    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sibi",
                                    "name": "Sibi",
                                    "subOptions": [
                                        {
                                            "key": " Kotmandai",
                                            "name": " Kotmandai    "
                                        },
                                        {
                                            "key": "Sangan",
                                            "name": "Sangan     "
                                        },
                                        {
                                            "key": "Sibi ",
                                            "name": "Sibi     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sohbatpur",
                                    "name": "Sohbatpur",
                                    "subOptions": [
                                        {
                                            "key": " Faridabad",
                                            "name": " Faridabad    "
                                        },
                                        {
                                            "key": "Sanhri",
                                            "name": "Sanhri     "
                                        },
                                        {
                                            "key": "Sohbatpur ",
                                            "name": "Sohbatpur     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Washuk",
                                    "name": "Washuk",
                                    "subOptions": [
                                        {
                                            "key": " Besima",
                                            "name": " Besima    "
                                        },
                                        {
                                            "key": "Musakhel",
                                            "name": "Musakhel     "
                                        },
                                        {
                                            "key": "Nag ",
                                            "name": "Nag     "
                                        },
                                        {
                                            "key": "Shahoo Garhi ",
                                            "name": "Shahoo Garhi     "
                                        },
                                        {
                                            "key": "Washuk ",
                                            "name": "Washuk     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Zhob",
                                    "name": "Zhob",
                                    "subOptions": [
                                        {
                                            "key": " Faridabad",
                                            "name": " Faridabad    "
                                        },
                                        {
                                            "key": "Sanhri",
                                            "name": "Sanhri     "
                                        },
                                        {
                                            "key": "Sohbatpur ",
                                            "name": "Sohbatpur     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Ziarat",
                                    "name": "Ziarat",
                                    "subOptions": [
                                        {
                                            "key": " Ashwat",
                                            "name": " Ashwat    "
                                        },
                                        {
                                            "key": "Kashatoo",
                                            "name": "Kashatoo     "
                                        },
                                        {
                                            "key": "Qamar Din Karez ",
                                            "name": "Qamar Din Karez     "
                                        },
                                        {
                                            "key": "Sambaza ",
                                            "name": "Sambaza     "
                                        },
                                        {
                                            "key": "Zhob ",
                                            "name": "Zhob     "
                                        }
                                    ]
                                }
                            ]
                        },
                        {
                            "key": "Sindh",
                            "name": "Sindh",
                            "subOptions": [
                                {
                                    "key": "Badin",
                                    "name": "Badin",
                                    "subOptions": [
                                        {
                                            "key": " Badin",
                                            "name": " Badin    "
                                        },
                                        {
                                            "key": "Golarchi",
                                            "name": "Golarchi     "
                                        },
                                        {
                                            "key": "Matli ",
                                            "name": "Matli     "
                                        },
                                        {
                                            "key": "Talhar ",
                                            "name": "Talhar     "
                                        },
                                        {
                                            "key": "Tando Bago ",
                                            "name": "Tando Bago     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Dadu",
                                    "name": "Dadu",
                                    "subOptions": [
                                        {
                                            "key": " Dadu",
                                            "name": " Dadu    "
                                        },
                                        {
                                            "key": "Johi",
                                            "name": "Johi     "
                                        },
                                        {
                                            "key": "Khairpur Nathan Shah ",
                                            "name": "Khairpur Nathan Shah     "
                                        },
                                        {
                                            "key": "Mehar ",
                                            "name": "Mehar     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Ghotki",
                                    "name": "Ghotki",
                                    "subOptions": [
                                        {
                                            "key": " Daharki",
                                            "name": " Daharki    "
                                        },
                                        {
                                            "key": "Ghotki",
                                            "name": "Ghotki     "
                                        },
                                        {
                                            "key": "Khangarh ",
                                            "name": "Khangarh    "
                                        },
                                        {
                                            "key": "Mirpur Mathelo ",
                                            "name": "Mirpur Mathelo     "
                                        },
                                        {
                                            "key": "Ubauro ",
                                            "name": "Ubauro     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Hyderabad",
                                    "name": "Hyderabad",
                                    "subOptions": [
                                        {
                                            "key": " Hyderabad",
                                            "name": " Hyderabad    "
                                        },
                                        {
                                            "key": "Hyderabad Cit",
                                            "name": "Hyderabad Cit     "
                                        },
                                        {
                                            "key": "Latifabad ",
                                            "name": "Latifabad     "
                                        },
                                        {
                                            "key": "Qasimabad ",
                                            "name": "Qasimabad     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Jacobabad",
                                    "name": "Jacobabad",
                                    "subOptions": [
                                        {
                                            "key": " Garhi Khairo",
                                            "name": " Garhi Khairo    "
                                        },
                                        {
                                            "key": "Jacobabad",
                                            "name": "Jacobabad     "
                                        },
                                        {
                                            "key": "Thul ",
                                            "name": "Thul     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Jamshoro",
                                    "name": "Jamshoro",
                                    "subOptions": [
                                        {
                                            "key": " Kotri",
                                            "name": " Kotri    "
                                        },
                                        {
                                            "key": "Manjhand",
                                            "name": "Manjhand     "
                                        },
                                        {
                                            "key": "Sehwan ",
                                            "name": "Sehwan     "
                                        },
                                        {
                                            "key": "Thano Bula Khan ",
                                            "name": "Thano Bula Khan     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Karachi",
                                    "name": "Karachi Central",
                                    "subOptions": [
                                        {
                                            "key": " Gulberg",
                                            "name": " Gulberg    "
                                        },
                                        {
                                            "key": "Liaquatabad",
                                            "name": "Liaquatabad     "
                                        },
                                        {
                                            "key": "Nazimabad ",
                                            "name": "Nazimabad    "
                                        },
                                        {
                                            "key": "New Karachi ",
                                            "name": "New Karachi     "
                                        },
                                        {
                                            "key": "North Nazimabad ",
                                            "name": "North Nazimabad     "
                                        }
                                    ]
                                },
                                {
                                    "key": "KarachiEast",
                                    "name": "Karachi East",
                                    "subOptions": [
                                        {
                                            "key": " Faisal Cantonment",
                                            "name": " Faisal Cantonment    "
                                        },
                                        {
                                            "key": "Ferozabad",
                                            "name": "Ferozabad     "
                                        },
                                        {
                                            "key": "Gulshan-e-Iqbal ",
                                            "name": "Gulshan-e-Iqbal     "
                                        },
                                        {
                                            "key": "Gulzar-e-Hijri ",
                                            "name": "Gulzar-e-Hijri     "
                                        },
                                        {
                                            "key": "Jamshed Quarters ",
                                            "name": "Jamshed Quarters     "
                                        }
                                    ]
                                },
                                {
                                    "key": "KarachiWest",
                                    "name": "Karachi West",
                                    "subOptions": [
                                        {
                                            "key": " Baldia",
                                            "name": " Baldia    "
                                        },
                                        {
                                            "key": "Harbour",
                                            "name": "Harbour     "
                                        },
                                        {
                                            "key": "Mango Pir ",
                                            "name": "Mango Pir    "
                                        },
                                        {
                                            "key": "Manora Cantonment ",
                                            "name": "Manora Cantonment     "
                                        },
                                        {
                                            "key": "Mauripur ",
                                            "name": "Mauripur     "
                                        },
                                        {
                                            "key": "Mominabad ",
                                            "name": "Mominabad     "
                                        },
                                        {
                                            "key": "Orangi ",
                                            "name": "Orangi     "
                                        },
                                        {
                                            "key": "Sindh Industrial Trading Estate ",
                                            "name": "Sindh Industrial Trading Estate     "
                                        }
                                    ]
                                },
                                {
                                    "key": "KarachiSouth",
                                    "name": "Karachi South",
                                    "subOptions": [
                                        {
                                            "key": " Aram Bagh",
                                            "name": " Aram Bagh    "
                                        },
                                        {
                                            "key": "Civil Line",
                                            "name": "Civil Line     "
                                        },
                                        {
                                            "key": "Clifton ",
                                            "name": "Clifton     "
                                        },
                                        {
                                            "key": "Garden ",
                                            "name": "Garden     "
                                        },
                                        {
                                            "key": "Lyari ",
                                            "name": "Lyari     "
                                        },
                                        {
                                            "key": "Saddar ",
                                            "name": "Saddar     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kashmore",
                                    "name": "Kashmore",
                                    "subOptions": [
                                        {
                                            "key": " Kandhkot",
                                            "name": " Kandhkot    "
                                        },
                                        {
                                            "key": "Kashmore",
                                            "name": "Kashmore     "
                                        },
                                        {
                                            "key": "Tangwani ",
                                            "name": "Tangwani     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Khairpur",
                                    "name": "Khairpur",
                                    "subOptions": [
                                        {
                                            "key": " Faiz Ganj",
                                            "name": " Faiz Ganj    "
                                        },
                                        {
                                            "key": "Gambat",
                                            "name": "Gambat     "
                                        },
                                        {
                                            "key": "Khairpur ",
                                            "name": "Khairpur     "
                                        },
                                        {
                                            "key": "Kingri ",
                                            "name": "Kingri     "
                                        },
                                        {
                                            "key": "Kot Diji ",
                                            "name": "Kot Diji     "
                                        },
                                        {
                                            "key": "Mirwah ",
                                            "name": "KMirwah    "
                                        },
                                        {
                                            "key": "Nara ",
                                            "name": "Nara    "
                                        },
                                        {
                                            "key": "Sobho Dero ",
                                            "name": "Sobho Dero    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Korangi",
                                    "name": "Korangi",
                                    "subOptions": [
                                        {
                                            "key": " Korangi",
                                            "name": " Korangi    "
                                        },
                                        {
                                            "key": "Landhi",
                                            "name": "Landhi     "
                                        },
                                        {
                                            "key": "Model Colony ",
                                            "name": "Model Colony     "
                                        },
                                        {
                                            "key": "Shah Faisal ",
                                            "name": "Shah Faisal     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Larkana",
                                    "name": "Larkana",
                                    "subOptions": [
                                        {
                                            "key": " Bakrani",
                                            "name": " Bakrani    "
                                        },
                                        {
                                            "key": "Dokri",
                                            "name": "Dokri     "
                                        },
                                        {
                                            "key": "Larkana ",
                                            "name": "Larkana     "
                                        },
                                        {
                                            "key": "Ratodero ",
                                            "name": "Ratodero     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Malir",
                                    "name": "Malir",
                                    "subOptions": [
                                        {
                                            "key": " Airport",
                                            "name": " Airport    "
                                        },
                                        {
                                            "key": "Bin Qasim",
                                            "name": "Bin Qasim     "
                                        },
                                        {
                                            "key": "Gadap ",
                                            "name": "Gadap     "
                                        },
                                        {
                                            "key": "Ibrahim Hyderi ",
                                            "name": "Ibrahim Hyderi     "
                                        },
                                        {
                                            "key": "Korangi Creek Cantonment ",
                                            "name": "Korangi Creek Cantonment     "
                                        },
                                        {
                                            "key": "Malir Cantonmentt ",
                                            "name": "Malir Cantonment    "
                                        },
                                        {
                                            "key": "Murad Memon ",
                                            "name": "Murad Memon    "
                                        },
                                        {
                                            "key": "Shah Mureed ",
                                            "name": "Shah Mureed    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Matiari",
                                    "name": "Matiari",
                                    "subOptions": [
                                        {
                                            "key": " Hala",
                                            "name": " Hala    "
                                        },
                                        {
                                            "key": "Matiari",
                                            "name": "Matiari     "
                                        },
                                        {
                                            "key": "Saeedabad ",
                                            "name": "Saeedabad     "
                                        }
                                    ]
                                },
                                {
                                    "key": "MirpurKhas",
                                    "name": "Mirpur Khas",
                                    "subOptions": [
                                        {
                                            "key": " Digri",
                                            "name": " Digri    "
                                        },
                                        {
                                            "key": "Hussain Bux Mari",
                                            "name": "Hussain Bux Mari     "
                                        },
                                        {
                                            "key": "Jhudo ",
                                            "name": "Jhudo    "
                                        },
                                        {
                                            "key": "Kot Ghulam Muhammad ",
                                            "name": "Kot Ghulam Muhammad     "
                                        },
                                        {
                                            "key": "Mirpur Khas ",
                                            "name": "Mirpur Khas     "
                                        },
                                        {
                                            "key": "Shujaabad ",
                                            "name": "Shujaabad     "
                                        },
                                        {
                                            "key": "Sindhri ",
                                            "name": "Sindhri    "
                                        }
                                    ]
                                },
                                {
                                    "key": "NaushahroFeroze",
                                    "name": "Naushahro Feroze",
                                    "subOptions": [
                                        {
                                            "key": " Bhiria",
                                            "name": " Bhiria    "
                                        },
                                        {
                                            "key": "Kandiaro",
                                            "name": "Kandiaro     "
                                        },
                                        {
                                            "key": "Mehrabpur ",
                                            "name": "Mehrabpur     "
                                        },
                                        {
                                            "key": "Moro ",
                                            "name": "Moro     "
                                        },
                                        {
                                            "key": "Naushahro Feroze ",
                                            "name": "Naushahro Feroze     "
                                        },
                                        {
                                            "key": "Datta Khel ",
                                            "name": "Datta Khel     "
                                        },
                                        {
                                            "key": "Dossali ",
                                            "name": "Dossali     "
                                        },
                                        {
                                            "key": "Ghulam Khan ",
                                            "name": "Ghulam Khan     "
                                        },
                                        {
                                            "key": "Mir Ali ",
                                            "name": "Mir Ali     "
                                        },
                                        {
                                            "key": "Miran Shah ",
                                            "name": "Miran Shah     "
                                        },
                                        {
                                            "key": "Razmak ",
                                            "name": "Razmak     "
                                        },
                                        {
                                            "key": "Shewa ",
                                            "name": "Shewa     "
                                        },
                                        {
                                            "key": "Spinwam ",
                                            "name": "Spinwam     "
                                        }
                                    ]
                                },
                                {
                                    "key": "QambarShahdadkot",
                                    "name": "Qambar Shahdadkot",
                                    "subOptions": [
                                        {
                                            "key": " Kambar Ali Khan",
                                            "name": " Kambar Ali Khan    "
                                        },
                                        {
                                            "key": "Nasirabad",
                                            "name": "Nasirabad     "
                                        },
                                        {
                                            "key": "Miro Khan ",
                                            "name": "Miro Khan     "
                                        },
                                        {
                                            "key": "Qubo Saeed Khan ",
                                            "name": "Qubo Saeed Khan     "
                                        },
                                        {
                                            "key": "Shahdadkot ",
                                            "name": "Shahdadkot     "
                                        },
                                        {
                                            "key": "Sujawal ",
                                            "name": "Sujawal     "
                                        },
                                        {
                                            "key": "Warah ",
                                            "name": "Warah     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sanghar",
                                    "name": "Sanghar",
                                    "subOptions": [
                                        {
                                            "key": " Jam Nawaz Ali",
                                            "name": " Jam Nawaz Ali    "
                                        },
                                        {
                                            "key": "Khipro",
                                            "name": "Khipro     "
                                        },
                                        {
                                            "key": "Sanghar ",
                                            "name": "Sanghar     "
                                        },
                                        {
                                            "key": "Shahdadpur ",
                                            "name": "Shahdadpur     "
                                        },
                                        {
                                            "key": "Sinjhoro ",
                                            "name": "Sinjhoro     "
                                        },
                                        {
                                            "key": "Tando Adam ",
                                            "name": "Tando Adam     "
                                        }
                                    ]
                                },
                                {
                                    "key": "ShaheedBenazirAbad",
                                    "name": "Shaheed Benazir Abad",
                                    "subOptions": [
                                        {
                                            "key": " Daur",
                                            "name": " Daur    "
                                        },
                                        {
                                            "key": "Kazi Ahmed (Daulatpur)",
                                            "name": "Kazi Ahmed (Daulatpur)     "
                                        },
                                        {
                                            "key": "Nawabshah ",
                                            "name": "Nawabshah    "
                                        },
                                        {
                                            "key": "Sakrand ",
                                            "name": "Sakrand     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Shikarpur",
                                    "name": "Shikarpur",
                                    "subOptions": [
                                        {
                                            "key": " Garhi Yasin",
                                            "name": " Garhi Yasin    "
                                        },
                                        {
                                            "key": "Khanpur",
                                            "name": "Khanpur     "
                                        },
                                        {
                                            "key": "Lakhi ",
                                            "name": "Lakhi     "
                                        },
                                        {
                                            "key": "Shikarpur ",
                                            "name": "Shikarpur     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sujawal",
                                    "name": "Sujawal",
                                    "subOptions": [
                                        {
                                            "key": " Jati",
                                            "name": " Jati    "
                                        },
                                        {
                                            "key": "Kharo Chan",
                                            "name": "Kharo Chan     "
                                        },
                                        {
                                            "key": "Mirpur Bathoro ",
                                            "name": "Mirpur Bathoro     "
                                        },
                                        {
                                            "key": "Shah Bunder ",
                                            "name": "Shah Bunder     "
                                        },
                                        {
                                            "key": "Sujawal ",
                                            "name": "Sujawal     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Sukkur",
                                    "name": "Sukkur",
                                    "subOptions": [
                                        {
                                            "key": " New Sukkur",
                                            "name": " New Sukkur    "
                                        },
                                        {
                                            "key": "Pano Aqil",
                                            "name": "Pano Aqil     "
                                        },
                                        {
                                            "key": "Rohri ",
                                            "name": "Rohri     "
                                        },
                                        {
                                            "key": "Salehpat ",
                                            "name": "Salehpat     "
                                        },
                                        {
                                            "key": "Sukkur City ",
                                            "name": "Sukkur City     "
                                        }
                                    ]
                                },
                                {
                                    "key": "TandoAllahyar",
                                    "name": "Tando Allahyar",
                                    "subOptions": [
                                        {
                                            "key": " Chamber",
                                            "name": " Chamber    "
                                        },
                                        {
                                            "key": "Jhando Mari",
                                            "name": "Jhando Mari     "
                                        },
                                        {
                                            "key": "Tando Allahyar ",
                                            "name": "Tando Allahyar     "
                                        }
                                    ]
                                },
                                {
                                    "key": "TandoMuhammadKhan",
                                    "name": "Tando Muhammad Khan",
                                    "subOptions": [
                                        {
                                            "key": " Bulri Shah Karim",
                                            "name": " Bulri Shah Karim    "
                                        },
                                        {
                                            "key": "Tando Ghulam Hyder",
                                            "name": "Tando Ghulam Hyder     "
                                        },
                                        {
                                            "key": "Tando Muhammad Khan ",
                                            "name": "Tando Muhammad Khan     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Tharparkar",
                                    "name": "Tharparkar",
                                    "subOptions": [
                                        {
                                            "key": " Chachro",
                                            "name": " Chachro    "
                                        },
                                        {
                                            "key": "Dahli",
                                            "name": "Dahli     "
                                        },
                                        {
                                            "key": "Diplo ",
                                            "name": "Diplo     "
                                        },
                                        {
                                            "key": "Islamkot ",
                                            "name": "Islamkot     "
                                        },
                                        {
                                            "key": "Kaloi ",
                                            "name": "Kaloi     "
                                        },
                                        {
                                            "key": "Mithi ",
                                            "name": "Mithi     "
                                        },
                                        {
                                            "key": "Nagar Parkar ",
                                            "name": "Nagar Parkar     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Thatta",
                                    "name": "Thatta",
                                    "subOptions": [
                                        {
                                            "key": " Ghorabari",
                                            "name": " Ghorabari    "
                                        },
                                        {
                                            "key": "Keti Bunder",
                                            "name": "Keti Bunder     "
                                        },
                                        {
                                            "key": "Mirpur Sakro ",
                                            "name": "Mirpur Sakro     "
                                        },
                                        {
                                            "key": "Thatta ",
                                            "name": "Thatta     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Umerkot",
                                    "name": "Umerkot",
                                    "subOptions": [
                                        {
                                            "key": " Kunri",
                                            "name": " Kunri    "
                                        },
                                        {
                                            "key": "Pithoro",
                                            "name": "Pithoro     "
                                        },
                                        {
                                            "key": "Samaro ",
                                            "name": "Samaro    "
                                        },
                                        {
                                            "key": "Umerkot ",
                                            "name": "Umerkot     "
                                        }
                                    ]
                                }
                            ]
                        },
                        {
                            "key": "Khyber Pakhtunkhwa",
                            "name": "Khyber Pakhtunkhwa",
                            "subOptions": [
                                {
                                    "key": "Abbottabad",
                                    "name": "Abbottabad",
                                    "subOptions": [
                                        {
                                            "key": " Abbottabad",
                                            "name": " Abbottabad    "
                                        },
                                        {
                                            "key": "Havelian",
                                            "name": "Havelian     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Bannu",
                                    "name": "Bannu",
                                    "subOptions": [
                                        {
                                            "key": " Bannu",
                                            "name": " Bannu    "
                                        },
                                        {
                                            "key": "Domel",
                                            "name": "Domel     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Batagram",
                                    "name": "Batagram",
                                    "subOptions": [
                                        {
                                            "key": " Allai",
                                            "name": " Allai    "
                                        },
                                        {
                                            "key": "Batagram",
                                            "name": "Batagram     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Buner",
                                    "name": "Buner",
                                    "subOptions": [
                                        {
                                            "key": " Daggar/Buner",
                                            "name": " Daggar/Buner    "
                                        },
                                        {
                                            "key": "Gagra",
                                            "name": "Gagra     "
                                        },
                                        {
                                            "key": "Khado Khel ",
                                            "name": "Khado Khel    "
                                        },
                                        {
                                            "key": "Mandanr ",
                                            "name": "Mandanr     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Charsadda",
                                    "name": "Charsadda",
                                    "subOptions": [
                                        {
                                            "key": " Charsadda",
                                            "name": " Charsadda    "
                                        },
                                        {
                                            "key": "Shabqadar",
                                            "name": "Shabqadar     "
                                        },
                                        {
                                            "key": "Tangi ",
                                            "name": "Tangi    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Chitral",
                                    "name": "Chitral",
                                    "subOptions": [
                                        {
                                            "key": " Chitral",
                                            "name": " Chitral    "
                                        },
                                        {
                                            "key": "Mastuj",
                                            "name": "Mastuj     "
                                        }
                                    ]
                                },
                                {
                                    "key": "DeraIsmailKhan",
                                    "name": "Dera Ismail Khan",
                                    "subOptions": [
                                        {
                                            "key": " Daraban",
                                            "name": " Daraban    "
                                        },
                                        {
                                            "key": "Dera Ismail Khan",
                                            "name": "Dera Ismail Khan     "
                                        },
                                        {
                                            "key": "Kulachi ",
                                            "name": "Kulachi    "
                                        },
                                        {
                                            "key": "Paharpur ",
                                            "name": "Paharpur     "
                                        },
                                        {
                                            "key": "Paroa ",
                                            "name": "Paroa     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Hangu",
                                    "name": "Hangu",
                                    "subOptions": [
                                        {
                                            "key": " Hangu",
                                            "name": " Hangu    "
                                        },
                                        {
                                            "key": "Tall",
                                            "name": "Tall     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Haripur",
                                    "name": "Haripur",
                                    "subOptions": [
                                        {
                                            "key": " Ghazi",
                                            "name": " Ghazi    "
                                        },
                                        {
                                            "key": "Haripur",
                                            "name": "Haripur     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Karak",
                                    "name": "Karak ",
                                    "subOptions": [
                                        {
                                            "key": " Banda Daud Shah",
                                            "name": " Banda Daud Shah    "
                                        },
                                        {
                                            "key": "Karak",
                                            "name": "Karak     "
                                        },
                                        {
                                            "key": "Samaro ",
                                            "name": "Samaro    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kohat",
                                    "name": "Kohat",
                                    "subOptions": [
                                        {
                                            "key": " Kohat",
                                            "name": " Kohat    "
                                        },
                                        {
                                            "key": "Lachi",
                                            "name": "Lachi     "
                                        },
                                        {
                                            "key": "Dassu ",
                                            "name": "Dassu    "
                                        },
                                        {
                                            "key": "Kandia ",
                                            "name": "Kandia     "
                                        },
                                        {
                                            "key": "Palas ",
                                            "name": "Palas     "
                                        },
                                        {
                                            "key": "Pattan ",
                                            "name": "Pattan     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Kohistan",
                                    "name": "Kohistan",
                                    "subOptions": [
                                        {
                                            "key": " Dassu",
                                            "name": " Dassu    "
                                        },
                                        {
                                            "key": "Kandia",
                                            "name": "Kandia     "
                                        },
                                        {
                                            "key": "Palas ",
                                            "name": "Palas    "
                                        },
                                        {
                                            "key": "Pattan ",
                                            "name": "Pattan     "
                                        }
                                    ]
                                },
                                {
                                    "key": "LakkiMarwat",
                                    "name": "Lakki Marwat",
                                    "subOptions": [
                                        {
                                            "key": " Lakki Marwat",
                                            "name": " Lakki Marwat    "
                                        },
                                        {
                                            "key": "Naurang",
                                            "name": "Naurang     "
                                        }
                                    ]
                                },
                                {
                                    "key": "LowerDir",
                                    "name": "Lower Dir",
                                    "subOptions": [
                                        {
                                            "key": " Adenzai",
                                            "name": " Adenzai    "
                                        },
                                        {
                                            "key": "Lal Qilla",
                                            "name": "Lal Qilla     "
                                        },
                                        {
                                            "key": "Samarbagh ",
                                            "name": "Samarbagh    "
                                        },
                                        {
                                            "key": "Timergara ",
                                            "name": "Timergara     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Malakand",
                                    "name": "Malakand",
                                    "subOptions": [
                                        {
                                            "key": " Sam Ranizai",
                                            "name": " Sam Ranizai    "
                                        },
                                        {
                                            "key": "Swat Ranizai",
                                            "name": "Swat Ranizai     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Mansehra",
                                    "name": "Mansehra",
                                    "subOptions": [
                                        {
                                            "key": " Balakot",
                                            "name": " Balakot    "
                                        },
                                        {
                                            "key": "Mansehra",
                                            "name": "Mansehra     "
                                        },
                                        {
                                            "key": "Oghi ",
                                            "name": "Oghi    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Mardan",
                                    "name": "Mardan ",
                                    "subOptions": [
                                        {
                                            "key": " Katlang",
                                            "name": " Katlang    "
                                        },
                                        {
                                            "key": "Mardan",
                                            "name": "Mardan     "
                                        },
                                        {
                                            "key": "Takht Bhai ",
                                            "name": "Takht Bhai    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Nowshera",
                                    "name": "Nowshera ",
                                    "subOptions": [
                                        {
                                            "key": " Jehangira",
                                            "name": " Jehangira    "
                                        },
                                        {
                                            "key": "Nowshera",
                                            "name": "Nowshera     "
                                        },
                                        {
                                            "key": "Pabbi ",
                                            "name": "Pabbi    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Peshawar",
                                    "name": "Peshawar ",
                                    "subOptions": [
                                        {
                                            "key": " Peshawar",
                                            "name": " Peshawar    "
                                        },
                                        {
                                            "key": "Pishin",
                                            "name": "Pishin     "
                                        },
                                        {
                                            "key": "Saranan ",
                                            "name": "Saranan    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Shangla",
                                    "name": "Shangla",
                                    "subOptions": [
                                        {
                                            "key": " Alpuri",
                                            "name": " Alpuri    "
                                        },
                                        {
                                            "key": "Besham",
                                            "name": "Besham     "
                                        },
                                        {
                                            "key": "Puran ",
                                            "name": "Puran    "
                                        }
                                    ]
                                },
                                {
                                    "key": "Swabi",
                                    "name": "Swabi",
                                    "subOptions": [
                                        {
                                            "key": " Lahor",
                                            "name": " Lahor    "
                                        },
                                        {
                                            "key": "Rzzar",
                                            "name": "Rzzar     "
                                        },
                                        {
                                            "key": "Swabi ",
                                            "name": "Swabi    "
                                        },
                                        {
                                            "key": "Topi ",
                                            "name": "Topi     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Swat",
                                    "name": "Swat",
                                    "subOptions": [
                                        {
                                            "key": " Babuzai",
                                            "name": " Babuzai    "
                                        },
                                        {
                                            "key": "Bari Kot",
                                            "name": "Bari Kot     "
                                        },
                                        {
                                            "key": "Behrain ",
                                            "name": "Behrain    "
                                        },
                                        {
                                            "key": "Charbagh ",
                                            "name": "Charbagh     "
                                        },
                                        {
                                            "key": "Kabal ",
                                            "name": "Kabal     "
                                        },
                                        {
                                            "key": "Khawaza Khela ",
                                            "name": "Khawaza Khela     "
                                        },
                                        {
                                            "key": "Matta ",
                                            "name": "Matta     "
                                        }
                                    ]
                                },
                                {
                                    "key": "Tank",
                                    "name": "Tank",
                                    "subOptions": [
                                        {
                                            "key": " Tank",
                                            "name": " Tank    "
                                        },
                                        {
                                            "key": "Pithoro",
                                            "name": "Pithoro     "
                                        },
                                        {
                                            "key": "Samaro ",
                                            "name": "Samaro    "
                                        },
                                        {
                                            "key": "Umerkot ",
                                            "name": "Umerkot     "
                                        }
                                    ]
                                },
                                {
                                    "key": "TorGhar(KalaDhaka)",
                                    "name": "Tor Ghar (Kala Dhaka)",
                                    "subOptions": [
                                        {
                                            "key": " Judba",
                                            "name": " Judba    "
                                        },
                                        {
                                            "key": "Khander",
                                            "name": "Khander     "
                                        }
                                    ]
                                },
                                {
                                    "key": "UpperDir",
                                    "name": "Upper Dir ",
                                    "subOptions": [
                                        {
                                            "key": " Dir",
                                            "name": " Dir    "
                                        },
                                        {
                                            "key": "Shringal",
                                            "name": "Shringal     "
                                        },
                                        {
                                            "key": "Wari ",
                                            "name": "Wari    "
                                        }
                                    ]
                                }
                            ]
                        },
                        {
                            "key": "Islamabad",
                            "name": "Islamabad",
                            "subOptions": [
                                {
                                    "key": "Islamabad",
                                    "name": "Islamabad"
                                }
                            ]
                        },
                        {
                            "key": "FATA",
                            "name": "FATA",
                            "subOptions": [
                                {
                                    "key": "BajaurTribal",
                                    "name": "Bajaur Tribal"
                                },
                                {
                                    "key": "FrontierRegionBannu",
                                    "name": "Frontier Region Bannu"
                                },
                                {
                                    "key": "FrontierRegionDeraIsmailKhan",
                                    "name": "Frontier Region Dera Ismail Khan"
                                },
                                {
                                    "key": "FrontierRegionKohat",
                                    "name": "Frontier Region Kohat"
                                },
                                {
                                    "key": "FrontierRegionLakkiMarwat",
                                    "name": "Frontier Region Lakki Marwat"
                                },
                                {
                                    "key": "FrontierRegionPeshawar",
                                    "name": "Frontier Region Peshawar"
                                },
                                {
                                    "key": "FrontierRegionTank",
                                    "name": "Frontier Region Tank"
                                },
                                {
                                    "key": "KhyberTribal",
                                    "name": "Khyber Tribal"
                                },
                                {
                                    "key": "KurramTribal",
                                    "name": "Kurram Tribal"
                                },
                                {
                                    "key": "MohmandTribal",
                                    "name": "Mohmand Tribal"
                                },
                                {
                                    "key": "NorthWaziristan",
                                    "name": "North Waziristan"
                                },
                                {
                                    "key": "OrakzaiTribal",
                                    "name": "Orakzai Tribal"
                                },
                                {
                                    "key": "SouthWaziristan",
                                    "name": "South Waziristan"
                                }
                            ]
                        }
                    ]
                }
            ]
              ,
            normalizer(node) {
                return {
                    id: node.key,
                    label: node.name,
                    children: node.subOptions,
                }
            },
        }),
    }
    
</script>


