# Server Metrics 2026-03-12 17:18:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 40774.7 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1472159
telemt_connections_bad_total 20277
telemt_handshake_timeouts_total 13901
telemt_upstream_connect_attempt_total 8118
telemt_upstream_connect_success_total 8070
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 8118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 500
telemt_me_reconnect_attempts_total 14823
telemt_me_reconnect_success_total 5980
telemt_me_reader_eof_total 6496
telemt_me_idle_close_by_peer_total 6495
telemt_me_route_drop_no_conn_total 568597
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1380065
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6960
telemt_desync_full_logged_total 1759
telemt_desync_suppressed_total 5201
telemt_desync_frames_bucket_total{bucket="1_2"} 1807
telemt_desync_frames_bucket_total{bucket="3_10"} 2525
telemt_desync_frames_bucket_total{bucket="gt_10"} 2628
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6339
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 5967
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 1379566
telemt_user_connections_current{user="hello"} 1986
telemt_user_octets_from_client{user="hello"} 21244977192 (19.79 GB)
telemt_user_octets_to_client{user="hello"} 421790285280 (392.82 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70394.9 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641990
telemt_connections_bad_total 8556
telemt_handshake_timeouts_total 28898
telemt_upstream_connect_attempt_total 16778
telemt_upstream_connect_success_total 16771
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 13130
telemt_me_reconnect_success_total 13053
telemt_me_reader_eof_total 13880
telemt_me_idle_close_by_peer_total 13880
telemt_me_route_drop_no_conn_total 198990
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576512
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2400
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1661
telemt_desync_frames_bucket_total{bucket="1_2"} 1020
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 604
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 13185
telemt_me_writer_restored_same_endpoint_total 13044
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 577049
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 8869257567 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 213319067438 (198.67 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 70395.0 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1341367
telemt_connections_bad_total 6670
telemt_handshake_timeouts_total 96203
telemt_upstream_connect_attempt_total 16840
telemt_upstream_connect_success_total 16835
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1124
telemt_me_reconnect_attempts_total 14170
telemt_me_reconnect_success_total 12933
telemt_me_reader_eof_total 13638
telemt_me_idle_close_by_peer_total 13637
telemt_me_route_drop_no_conn_total 433256
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1009978
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4310
telemt_desync_full_logged_total 1333
telemt_desync_suppressed_total 2977
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 1564
telemt_desync_frames_bucket_total{bucket="gt_10"} 2077
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13034
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12892
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 1009825
telemt_user_connections_current{user="hello"} 1347
telemt_user_octets_from_client{user="hello"} 15050885216 (14.02 GB)
telemt_user_octets_to_client{user="hello"} 345450586557 (321.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 70395.5 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808602
telemt_connections_bad_total 8796
telemt_handshake_timeouts_total 62700
telemt_upstream_connect_attempt_total 18380
telemt_upstream_connect_success_total 18309
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 18380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1569
telemt_me_reconnect_attempts_total 20017
telemt_me_reconnect_success_total 14764
telemt_me_reader_eof_total 15724
telemt_me_idle_close_by_peer_total 15724
telemt_me_route_drop_no_conn_total 281771
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700172
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1536
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1022
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15042
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14743
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 699595
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 8600328876 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 280238058664 (260.99 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70395.3 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912385
telemt_connections_bad_total 11398
telemt_handshake_timeouts_total 7492
telemt_upstream_connect_attempt_total 22466
telemt_upstream_connect_success_total 22196
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 22466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 1279
telemt_me_reconnect_attempts_total 26682
telemt_me_reconnect_success_total 18632
telemt_me_reader_eof_total 19492
telemt_me_idle_close_by_peer_total 19492
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 332838
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837723
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3303
telemt_desync_full_logged_total 1126
telemt_desync_suppressed_total 2177
telemt_desync_frames_bucket_total{bucket="1_2"} 886
telemt_desync_frames_bucket_total{bucket="3_10"} 1131
telemt_desync_frames_bucket_total{bucket="gt_10"} 1286
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19086
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 18588
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 837606
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 10287778212 (9.58 GB)
telemt_user_octets_to_client{user="hello"} 253908990468 (236.47 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 132
```