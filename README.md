Sample APIs:


1. <b>Fetch list of tournaments:</b>

<b>GET</b> tournaments

Response:

    [{
        "tournament_id": 1,
        "tournament_name": "Tournament 1 name",
        "tournament_year": "2022",
        "venue": "Tournament 1 venue",
        "start_date": "2022-09-06",
        "end_date": "2022-09-10"
    }, {
        "tournament_id": 2,
        "tournament_name": "Tournament 2 name",
        "tournament_year": "2022",
        "venue": "Tournament 2 venue",
        "start_date": "2022-12-18",
        "end_date": "2022-12-24"
    }]


2. <b>Fetch game categories of a tournament:</b>

<b>GET</b> tournaments/1/fixtures

Response:

    [{
        "fixture_id": 8,
        "fixture_name": "Phunaba Ama U-18 Male -56Kg"
    }, {
        "fixture_id": 9,
        "fixture_name": "Phunaba Ama U-18 Female -52Kg"
    }, {
        "fixture_id": 10,
        "fixture_name": "Phunaba Ama U-18 Male -60Kg"
    }, {
        "fixture_id": 11,
        "fixture_name": "Phunaba Ama U-18 Female -56Kg"
    }, {
        "fixture_id": 12,
        "fixture_name": "Phunaba Ani U-18 Male -56Kg"
    }, {
        "fixture_id": 13,
        "fixture_name": "Phunaba Ani U-18 Female -52Kg"
    }, {
        "fixture_id": 14,
        "fixture_name": "Phunaba Ani U-18 Male -60Kg"
    }, {
        "fixture_id": 15,
        "fixture_name": "Phunaba Ani U-18 Female -56Kg"
    }]


3. <b>Fetch results of a fixture:</b>

<b>GET</b> fixtures/8/results

Response:

    [{
        "round_name": "Round of 16",
        "results": [{
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 82,
                "kit_id": "GAAA005F09",
                "player_name": "Tomba",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 45,
                "kit_id": "GAAA005F10",
                "player_name": "Chaoba",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 82
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 90,
                "kit_id": "GAAA005F18",
                "player_name": "Santosh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 92
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 90,
                "kit_id": "GAAA005F18",
                "player_name": "Santosh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 92
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 90,
                "kit_id": "GAAA005F18",
                "player_name": "Santosh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 92
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 90,
                "kit_id": "GAAA005F18",
                "player_name": "Santosh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 92
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 90,
                "kit_id": "GAAA005F18",
                "player_name": "Santosh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 92
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 90,
                "kit_id": "GAAA005F18",
                "player_name": "Santosh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 92
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 90,
                "kit_id": "GAAA005F18",
                "player_name": "Santosh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 92
        }]
    }, {
        "round_name": "Quarter Final",
        "results": [{
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 82,
                "kit_id": "GAAA005F09",
                "player_name": "Tomba",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 92
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 102,
                "kit_id": "GAAA005F32",
                "player_name": "Rakesh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 21,
                "kit_id": "GAAA005F19",
                "player_name": "Himmat",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 21
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 102,
                "kit_id": "GAAA005F32",
                "player_name": "Rakesh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 21,
                "kit_id": "GAAA005F19",
                "player_name": "Himmat",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 21
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 102,
                "kit_id": "GAAA005F32",
                "player_name": "Rakesh",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 21,
                "kit_id": "GAAA005F19",
                "player_name": "Himmat",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 21
        }]
    }, {
        "round_name": "Quarter Final",
        "results": [{
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 21,
                "kit_id": "GAAA005F19",
                "player_name": "Himmat",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 21
        }, {
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 180,
                "kit_id": "GAAA005F09",
                "player_name": "Prakash",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 12,
                "kit_id": "GAAA005H12",
                "player_name": "Prem",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 12
        }]
    }, {
        "round_name": "Third Place",
        "results": [{
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 92,
                "kit_id": "GAAA005G09",
                "player_name": "Rahul",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 180,
                "kit_id": "GAAA005F09",
                "player_name": "Prakash",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 180
        }]
    }, {
        "round_name": "Final",
        "results": [{
            "schedule_date": "2022-09-06",
            "schedule_time": "09:00",
            "players": [{
                "player_id": 12,
                "kit_id": "GAAA005H12",
                "player_name": "Prem",
                "color": "Red",
                "points": 15,
                "state_name": "Manipur",
                "state_id": 24
            }, {
                "player_id": 21,
                "kit_id": "GAAA005F19",
                "player_name": "Himmat",
                "color": "Blue",
                "points": 14,
                "state_name": "Manipur",
                "state_id": 24
            }],
            "winner_payer_id": 21
        }]
    }]


Note: "results" will be empty array [] if players are not yet determined.
For example, if quarter final is not yet played, then the "results" for semi final & final will be []
