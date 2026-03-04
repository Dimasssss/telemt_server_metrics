# Server Metrics 2026-03-04 10:36:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 48329.7 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717742
telemt_connections_bad_total 11052
telemt_handshake_timeouts_total 8127
telemt_upstream_connect_attempt_total 31268
telemt_upstream_connect_success_total 31140
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 31140
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 338
telemt_me_reconnect_attempts_total 7050
telemt_me_reconnect_success_total 7005
telemt_me_reader_eof_total 7225
telemt_me_idle_close_by_peer_total 7225
telemt_me_route_drop_no_conn_total 278341
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1231
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 806
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7225
telemt_me_writer_restored_same_endpoint_total 6984
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 594527
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 6653048940 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 179689086540 (167.35 GB)
telemt_user_unique_ips_current{user="hello"} 98
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 48326.4 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286348
telemt_connections_bad_total 2729
telemt_handshake_timeouts_total 26790
telemt_upstream_connect_attempt_total 94924
telemt_upstream_connect_success_total 93539
telemt_upstream_connect_fail_total 654
telemt_upstream_connect_attempts_per_request{bucket="1"} 93533
telemt_upstream_connect_attempts_per_request{bucket="2"} 660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 654
telemt_me_keepalive_timeout_total 1356
telemt_me_reconnect_attempts_total 54411
telemt_me_reconnect_success_total 54327
telemt_me_reader_eof_total 55727
telemt_me_idle_close_by_peer_total 55726
telemt_me_route_drop_no_conn_total 128688
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 204
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 577
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55807
telemt_me_writer_restored_same_endpoint_total 54302
telemt_me_writer_removed_unexpected_minus_restored_total 1505
telemt_user_connections_total{user="hello"} 222505
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 2654705112 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 74738194212 (69.61 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 48325.2 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571273
telemt_connections_bad_total 146553
telemt_handshake_timeouts_total 17585
telemt_upstream_connect_attempt_total 71101
telemt_upstream_connect_success_total 70670
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 70669
telemt_upstream_connect_attempts_per_request{bucket="2"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 926
telemt_me_reconnect_attempts_total 32743
telemt_me_reconnect_success_total 32658
telemt_me_reader_eof_total 34423
telemt_me_idle_close_by_peer_total 34419
telemt_me_route_drop_no_conn_total 205174
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 960
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 347
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 34435
telemt_me_writer_restored_same_endpoint_total 32637
telemt_me_writer_removed_unexpected_minus_restored_total 1798
telemt_user_connections_total{user="hello"} 388844
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 4681234116 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 134785702532 (125.53 GB)
telemt_user_unique_ips_current{user="hello"} 69
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 48324.1 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375017
telemt_connections_bad_total 25605
telemt_handshake_timeouts_total 66015
telemt_upstream_connect_attempt_total 34890
telemt_upstream_connect_success_total 34749
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 34749
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 392
telemt_me_reconnect_attempts_total 6994
telemt_me_reconnect_success_total 6970
telemt_me_reader_eof_total 7109
telemt_me_idle_close_by_peer_total 7109
telemt_me_route_drop_no_conn_total 104265
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 204
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 13
telemt_pool_force_close_total 316
telemt_me_writer_removed_unexpected_total 7109
telemt_me_writer_restored_same_endpoint_total 6949
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 261715
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 2845847784 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 94749898384 (88.24 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 48322.8 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505175
telemt_connections_bad_total 6809
telemt_handshake_timeouts_total 132329
telemt_upstream_connect_attempt_total 69533
telemt_upstream_connect_success_total 69078
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 69078
telemt_upstream_connect_attempts_per_request{bucket="2"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 910
telemt_me_reconnect_attempts_total 33721
telemt_me_reconnect_success_total 33689
telemt_me_reader_eof_total 35369
telemt_me_idle_close_by_peer_total 35368
telemt_me_route_drop_no_conn_total 158208
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 541
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35381
telemt_me_writer_restored_same_endpoint_total 33664
telemt_me_writer_removed_unexpected_minus_restored_total 1717
telemt_user_connections_total{user="hello"} 344946
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 4633426688 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 90689731884 (84.46 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 44
```