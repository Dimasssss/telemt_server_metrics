# Server Metrics 2026-03-12 19:00:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 46908.6 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1670791
telemt_connections_bad_total 20515
telemt_handshake_timeouts_total 15722
telemt_upstream_connect_attempt_total 9291
telemt_upstream_connect_success_total 9239
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 15681
telemt_me_reconnect_success_total 6835
telemt_me_reader_eof_total 7398
telemt_me_idle_close_by_peer_total 7397
telemt_me_route_drop_no_conn_total 652778
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1561874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7941
telemt_desync_full_logged_total 2018
telemt_desync_suppressed_total 5923
telemt_desync_frames_bucket_total{bucket="1_2"} 2066
telemt_desync_frames_bucket_total{bucket="3_10"} 2872
telemt_desync_frames_bucket_total{bucket="gt_10"} 3003
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7206
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6822
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 1561363
telemt_user_connections_current{user="hello"} 1585
telemt_user_octets_from_client{user="hello"} 24247766504 (22.58 GB)
telemt_user_octets_to_client{user="hello"} 532353317092 (495.79 GB)
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76529.1 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714086
telemt_connections_bad_total 9472
telemt_handshake_timeouts_total 29601
telemt_upstream_connect_attempt_total 19489
telemt_upstream_connect_success_total 19460
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3367
telemt_me_reconnect_attempts_total 14071
telemt_me_reconnect_success_total 13986
telemt_me_reader_eof_total 14869
telemt_me_idle_close_by_peer_total 14869
telemt_me_route_drop_no_conn_total 227983
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 643189
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2826
telemt_desync_full_logged_total 865
telemt_desync_suppressed_total 1961
telemt_desync_frames_bucket_total{bucket="1_2"} 1118
telemt_desync_frames_bucket_total{bucket="3_10"} 922
telemt_desync_frames_bucket_total{bucket="gt_10"} 786
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 14136
telemt_me_writer_restored_same_endpoint_total 13977
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 645068
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 10347564500 (9.64 GB)
telemt_user_octets_to_client{user="hello"} 242479427087 (225.83 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 76529.0 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1478924
telemt_connections_bad_total 7177
telemt_handshake_timeouts_total 101897
telemt_upstream_connect_attempt_total 18146
telemt_upstream_connect_success_total 18140
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 15196
telemt_me_reconnect_success_total 13952
telemt_me_reader_eof_total 14711
telemt_me_idle_close_by_peer_total 14710
telemt_me_route_drop_no_conn_total 487443
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130439
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4718
telemt_desync_full_logged_total 1455
telemt_desync_suppressed_total 3263
telemt_desync_frames_bucket_total{bucket="1_2"} 742
telemt_desync_frames_bucket_total{bucket="3_10"} 1709
telemt_desync_frames_bucket_total{bucket="gt_10"} 2267
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14077
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13911
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 1130302
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 17773042876 (16.55 GB)
telemt_user_octets_to_client{user="hello"} 414020503265 (385.59 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 76529.6 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 903042
telemt_connections_bad_total 12954
telemt_handshake_timeouts_total 66693
telemt_upstream_connect_attempt_total 19702
telemt_upstream_connect_success_total 19625
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 19702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 1638
telemt_me_reconnect_attempts_total 23534
telemt_me_reconnect_success_total 15809
telemt_me_reader_eof_total 16887
telemt_me_idle_close_by_peer_total 16887
telemt_me_route_drop_no_conn_total 318462
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780935
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 16179
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15788
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 780293
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 10398688508 (9.68 GB)
telemt_user_octets_to_client{user="hello"} 321396212412 (299.32 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76529.4 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1012033
telemt_connections_bad_total 11529
telemt_handshake_timeouts_total 8329
telemt_upstream_connect_attempt_total 23933
telemt_upstream_connect_success_total 23646
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 23933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_keepalive_timeout_total 1390
telemt_me_reconnect_attempts_total 30848
telemt_me_reconnect_success_total 19814
telemt_me_reader_eof_total 20817
telemt_me_idle_close_by_peer_total 20817
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 377576
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 928609
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3508
telemt_desync_full_logged_total 1222
telemt_desync_suppressed_total 2286
telemt_desync_frames_bucket_total{bucket="1_2"} 988
telemt_desync_frames_bucket_total{bucket="3_10"} 1171
telemt_desync_frames_bucket_total{bucket="gt_10"} 1349
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 20382
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19770
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 928480
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 11519832008 (10.73 GB)
telemt_user_octets_to_client{user="hello"} 312761924860 (291.28 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 115
```