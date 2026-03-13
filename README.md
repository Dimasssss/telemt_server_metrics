# Server Metrics 2026-03-13 21:48:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 143380.3 (39h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4497085
telemt_connections_bad_total 38136
telemt_handshake_timeouts_total 106727
telemt_upstream_connect_attempt_total 29974
telemt_upstream_connect_success_total 29766
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 29974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6621
telemt_me_reconnect_attempts_total 30391
telemt_me_reconnect_success_total 20271
telemt_me_reader_eof_total 21752
telemt_me_idle_close_by_peer_total 21751
telemt_me_route_drop_no_conn_total 1696903
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4120334
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16408
telemt_desync_full_logged_total 4394
telemt_desync_suppressed_total 12014
telemt_desync_frames_bucket_total{bucket="1_2"} 4090
telemt_desync_frames_bucket_total{bucket="3_10"} 6267
telemt_desync_frames_bucket_total{bucket="gt_10"} 6051
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 20879
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20258
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 608
telemt_user_connections_total{user="hello"} 4122463
telemt_user_connections_current{user="hello"} 863
telemt_user_octets_from_client{user="hello"} 60551236232 (56.39 GB)
telemt_user_octets_to_client{user="hello"} 1305743842985 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43044.1 (11h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 579345
telemt_connections_bad_total 41512
telemt_handshake_timeouts_total 12352
telemt_upstream_connect_attempt_total 12179
telemt_upstream_connect_success_total 11955
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 1900
telemt_me_reconnect_attempts_total 11199
telemt_me_reconnect_success_total 7773
telemt_me_reader_eof_total 8224
telemt_me_idle_close_by_peer_total 8223
telemt_me_route_drop_no_conn_total 212520
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502709
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7989
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7765
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 504640
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 5441311801 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 165282988272 (153.93 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 173000.7 (48h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3272063
telemt_connections_bad_total 31395
telemt_handshake_timeouts_total 219411
telemt_upstream_connect_attempt_total 38396
telemt_upstream_connect_success_total 38375
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10260
telemt_me_reconnect_attempts_total 34372
telemt_me_reconnect_success_total 29422
telemt_me_reader_eof_total 31228
telemt_me_idle_close_by_peer_total 31227
telemt_me_route_drop_no_conn_total 1119863
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2714900
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8922
telemt_desync_full_logged_total 2994
telemt_desync_suppressed_total 5928
telemt_desync_frames_bucket_total{bucket="1_2"} 1470
telemt_desync_frames_bucket_total{bucket="3_10"} 3249
telemt_desync_frames_bucket_total{bucket="gt_10"} 4203
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 29856
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29381
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 2714165
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 44428632480 (41.38 GB)
telemt_user_octets_to_client{user="hello"} 958560898449 (892.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 173003.5 (48h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2130204
telemt_connections_bad_total 22813
telemt_handshake_timeouts_total 211269
telemt_upstream_connect_attempt_total 53745
telemt_upstream_connect_success_total 51300
telemt_upstream_connect_fail_total 2308
telemt_upstream_connect_attempts_per_request{bucket="1"} 53471
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2307
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20238
telemt_me_reconnect_attempts_total 44658
telemt_me_reconnect_success_total 35645
telemt_me_reader_eof_total 38246
telemt_me_idle_close_by_peer_total 38239
telemt_me_route_drop_no_conn_total 749375
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1746744
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3782
telemt_desync_full_logged_total 1209
telemt_desync_suppressed_total 2573
telemt_desync_frames_bucket_total{bucket="1_2"} 998
telemt_desync_frames_bucket_total{bucket="3_10"} 1578
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 36234
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35621
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 1752625
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 27178938427 (25.31 GB)
telemt_user_octets_to_client{user="hello"} 655696557634 (610.67 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42436.6 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618873
telemt_connections_bad_total 5844
telemt_handshake_timeouts_total 5692
telemt_upstream_connect_attempt_total 9582
telemt_upstream_connect_success_total 9268
telemt_upstream_connect_fail_total 314
telemt_upstream_connect_attempts_per_request{bucket="1"} 9582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 314
telemt_me_keepalive_timeout_total 978
telemt_me_reconnect_attempts_total 32026
telemt_me_reconnect_success_total 7117
telemt_me_reader_eof_total 8027
telemt_me_idle_close_by_peer_total 8026
telemt_me_route_drop_no_conn_total 235339
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 579954
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1534
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1054
telemt_desync_frames_bucket_total{bucket="1_2"} 466
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7957
telemt_me_refill_failed_total 776
telemt_me_writer_restored_same_endpoint_total 7113
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 840
telemt_user_connections_total{user="hello"} 579866
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 8552098944 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 184610535040 (171.93 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 34
```