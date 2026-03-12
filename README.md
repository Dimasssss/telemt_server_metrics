# Server Metrics 2026-03-12 20:37:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 52728.8 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1808783
telemt_connections_bad_total 20723
telemt_handshake_timeouts_total 19884
telemt_upstream_connect_attempt_total 10256
telemt_upstream_connect_success_total 10195
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 16379
telemt_me_reconnect_success_total 7529
telemt_me_reader_eof_total 8147
telemt_me_idle_close_by_peer_total 8146
telemt_me_route_drop_no_conn_total 711847
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1688272
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8280
telemt_desync_full_logged_total 2139
telemt_desync_suppressed_total 6141
telemt_desync_frames_bucket_total{bucket="1_2"} 2166
telemt_desync_frames_bucket_total{bucket="3_10"} 2990
telemt_desync_frames_bucket_total{bucket="gt_10"} 3124
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7914
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7516
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 1687756
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 25935021508 (24.15 GB)
telemt_user_octets_to_client{user="hello"} 587663220952 (547.30 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82349.4 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761069
telemt_connections_bad_total 10849
telemt_handshake_timeouts_total 30350
telemt_upstream_connect_attempt_total 20863
telemt_upstream_connect_success_total 20834
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3386
telemt_me_reconnect_attempts_total 15151
telemt_me_reconnect_success_total 15060
telemt_me_reader_eof_total 16014
telemt_me_idle_close_by_peer_total 16014
telemt_me_route_drop_no_conn_total 244590
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686811
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2935
telemt_desync_full_logged_total 900
telemt_desync_suppressed_total 2035
telemt_desync_frames_bucket_total{bucket="1_2"} 1136
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15213
telemt_me_writer_restored_same_endpoint_total 15051
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 688683
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 11757682192 (10.95 GB)
telemt_user_octets_to_client{user="hello"} 262133068367 (244.13 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 82349.3 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1572253
telemt_connections_bad_total 7539
telemt_handshake_timeouts_total 107788
telemt_upstream_connect_attempt_total 19343
telemt_upstream_connect_success_total 19337
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1205
telemt_me_reconnect_attempts_total 16099
telemt_me_reconnect_success_total 14852
telemt_me_reader_eof_total 15676
telemt_me_idle_close_by_peer_total 15675
telemt_me_route_drop_no_conn_total 519537
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1213038
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4825
telemt_desync_full_logged_total 1484
telemt_desync_suppressed_total 3341
telemt_desync_frames_bucket_total{bucket="1_2"} 769
telemt_desync_frames_bucket_total{bucket="3_10"} 1744
telemt_desync_frames_bucket_total{bucket="gt_10"} 2312
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 14991
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14811
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1212646
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 19113776948 (17.80 GB)
telemt_user_octets_to_client{user="hello"} 452703288405 (421.61 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 82349.8 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966474
telemt_connections_bad_total 12970
telemt_handshake_timeouts_total 70683
telemt_upstream_connect_attempt_total 21025
telemt_upstream_connect_success_total 20942
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 21025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1671
telemt_me_reconnect_attempts_total 24548
telemt_me_reconnect_success_total 16822
telemt_me_reader_eof_total 17972
telemt_me_idle_close_by_peer_total 17972
telemt_me_route_drop_no_conn_total 344727
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 839111
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1779
telemt_desync_full_logged_total 592
telemt_desync_suppressed_total 1187
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 17198
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16801
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 838461
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 13116781004 (12.22 GB)
telemt_user_octets_to_client{user="hello"} 342535382960 (319.01 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82349.7 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1084872
telemt_connections_bad_total 12398
telemt_handshake_timeouts_total 8961
telemt_upstream_connect_attempt_total 25587
telemt_upstream_connect_success_total 25276
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 25587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1422
telemt_me_reconnect_attempts_total 32176
telemt_me_reconnect_success_total 21138
telemt_me_reader_eof_total 22212
telemt_me_idle_close_by_peer_total 22212
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 405980
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 995788
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3723
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 2418
telemt_desync_frames_bucket_total{bucket="1_2"} 1070
telemt_desync_frames_bucket_total{bucket="3_10"} 1236
telemt_desync_frames_bucket_total{bucket="gt_10"} 1417
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 21723
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21094
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 995657
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 12405364084 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 350109767348 (326.07 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 47
```