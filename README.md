# Server Metrics 2026-03-11 18:46:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 101958.7 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2586923
telemt_connections_bad_total 48538
telemt_handshake_timeouts_total 56734
telemt_upstream_connect_attempt_total 21510
telemt_upstream_connect_success_total 21498
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5315
telemt_me_reconnect_attempts_total 34207
telemt_me_reconnect_success_total 16326
telemt_me_reader_eof_total 17662
telemt_me_idle_close_by_peer_total 17662
telemt_me_route_drop_no_conn_total 972721
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2366428
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11994
telemt_desync_full_logged_total 3315
telemt_desync_suppressed_total 8679
telemt_desync_frames_bucket_total{bucket="1_2"} 2947
telemt_desync_frames_bucket_total{bucket="3_10"} 4629
telemt_desync_frames_bucket_total{bucket="gt_10"} 4418
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 17066
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16320
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 2364804
telemt_user_connections_current{user="hello"} 1264
telemt_user_octets_from_client{user="hello"} 35332711160 (32.91 GB)
telemt_user_octets_to_client{user="hello"} 671057833584 (624.97 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 102015.4 (28h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 967724
telemt_connections_bad_total 16418
telemt_handshake_timeouts_total 86094
telemt_upstream_connect_attempt_total 31640
telemt_upstream_connect_success_total 28671
telemt_upstream_connect_fail_total 2969
telemt_upstream_connect_attempts_per_request{bucket="1"} 31640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2969
telemt_me_keepalive_timeout_total 2829
telemt_me_reconnect_attempts_total 22690
telemt_me_reconnect_success_total 20579
telemt_me_reader_eof_total 21779
telemt_me_idle_close_by_peer_total 21776
telemt_me_route_drop_no_conn_total 365568
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807402
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3192
telemt_desync_full_logged_total 1033
telemt_desync_suppressed_total 2159
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 1141
telemt_desync_frames_bucket_total{bucket="gt_10"} 1048
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20867
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20556
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 809854
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 9759439650 (9.09 GB)
telemt_user_octets_to_client{user="hello"} 233593604348 (217.55 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 102015.4 (28h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1664390
telemt_connections_bad_total 10440
telemt_handshake_timeouts_total 133316
telemt_upstream_connect_attempt_total 26496
telemt_upstream_connect_success_total 26164
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 26496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 1969
telemt_me_reconnect_attempts_total 48265
telemt_me_reconnect_success_total 19922
telemt_me_reader_eof_total 21665
telemt_me_idle_close_by_peer_total 21665
telemt_me_route_drop_no_conn_total 605906
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1457305
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4023
telemt_desync_full_logged_total 1178
telemt_desync_suppressed_total 2845
telemt_desync_frames_bucket_total{bucket="1_2"} 941
telemt_desync_frames_bucket_total{bucket="3_10"} 1525
telemt_desync_frames_bucket_total{bucket="gt_10"} 1557
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21085
telemt_me_refill_failed_total 880
telemt_me_writer_restored_same_endpoint_total 19910
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1163
telemt_user_connections_total{user="hello"} 1456979
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 18085636541 (16.84 GB)
telemt_user_octets_to_client{user="hello"} 443694913397 (413.22 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 102015.9 (28h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1185929
telemt_connections_bad_total 78200
telemt_handshake_timeouts_total 109975
telemt_upstream_connect_attempt_total 27476
telemt_upstream_connect_success_total 27476
telemt_upstream_connect_attempts_per_request{bucket="1"} 27476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1416
telemt_me_reconnect_attempts_total 26971
telemt_me_reconnect_success_total 22360
telemt_me_reader_eof_total 23747
telemt_me_idle_close_by_peer_total 23746
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 395632
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 963188
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2026
telemt_desync_full_logged_total 775
telemt_desync_suppressed_total 1251
telemt_desync_frames_bucket_total{bucket="1_2"} 732
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 22740
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22327
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 962449
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 11435296176 (10.65 GB)
telemt_user_octets_to_client{user="hello"} 292586536920 (272.49 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6691.7 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110766
telemt_connections_bad_total 406
telemt_handshake_timeouts_total 651
telemt_upstream_connect_attempt_total 1889
telemt_upstream_connect_success_total 1888
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1510
telemt_me_reconnect_success_total 1493
telemt_me_reader_eof_total 1521
telemt_me_idle_close_by_peer_total 1521
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 38174
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102146
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 220
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1509
telemt_me_writer_restored_same_endpoint_total 1469
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 102122
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 6384185044 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 34921569220 (32.52 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 88
```