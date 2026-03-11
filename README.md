# Server Metrics 2026-03-11 20:43:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 108998.2 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2763544
telemt_connections_bad_total 58510
telemt_handshake_timeouts_total 62222
telemt_upstream_connect_attempt_total 23088
telemt_upstream_connect_success_total 23076
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5414
telemt_me_reconnect_attempts_total 35446
telemt_me_reconnect_success_total 17552
telemt_me_reader_eof_total 18945
telemt_me_idle_close_by_peer_total 18945
telemt_me_route_drop_no_conn_total 1038957
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2512037
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12664
telemt_desync_full_logged_total 3517
telemt_desync_suppressed_total 9147
telemt_desync_frames_bucket_total{bucket="1_2"} 3123
telemt_desync_frames_bucket_total{bucket="3_10"} 4867
telemt_desync_frames_bucket_total{bucket="gt_10"} 4674
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18315
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17546
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 2510379
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 38084412260 (35.47 GB)
telemt_user_octets_to_client{user="hello"} 723706544148 (674.00 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 109054.9 (30h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1013307
telemt_connections_bad_total 17046
telemt_handshake_timeouts_total 90415
telemt_upstream_connect_attempt_total 33323
telemt_upstream_connect_success_total 30348
telemt_upstream_connect_fail_total 2975
telemt_upstream_connect_attempts_per_request{bucket="1"} 33323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2089
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2975
telemt_me_keepalive_timeout_total 2888
telemt_me_reconnect_attempts_total 24020
telemt_me_reconnect_success_total 21893
telemt_me_reader_eof_total 23198
telemt_me_idle_close_by_peer_total 23195
telemt_me_route_drop_no_conn_total 383522
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846409
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3356
telemt_desync_full_logged_total 1092
telemt_desync_suppressed_total 2264
telemt_desync_frames_bucket_total{bucket="1_2"} 1091
telemt_desync_frames_bucket_total{bucket="3_10"} 1182
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 22217
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21870
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 848848
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 10277068130 (9.57 GB)
telemt_user_octets_to_client{user="hello"} 250054195024 (232.88 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 109054.9 (30h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1762726
telemt_connections_bad_total 11155
telemt_handshake_timeouts_total 135541
telemt_upstream_connect_attempt_total 27566
telemt_upstream_connect_success_total 27214
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 27566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_keepalive_timeout_total 2030
telemt_me_reconnect_attempts_total 58734
telemt_me_reconnect_success_total 20597
telemt_me_reader_eof_total 22648
telemt_me_idle_close_by_peer_total 22648
telemt_me_route_drop_no_conn_total 640818
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1550371
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4174
telemt_desync_full_logged_total 1230
telemt_desync_suppressed_total 2944
telemt_desync_frames_bucket_total{bucket="1_2"} 971
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1616
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22071
telemt_me_refill_failed_total 1186
telemt_me_writer_restored_same_endpoint_total 20585
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1474
telemt_user_connections_total{user="hello"} 1550001
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 19873853289 (18.51 GB)
telemt_user_octets_to_client{user="hello"} 474980402857 (442.36 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 109055.2 (30h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1260624
telemt_connections_bad_total 78249
telemt_handshake_timeouts_total 111519
telemt_upstream_connect_attempt_total 29350
telemt_upstream_connect_success_total 29350
telemt_upstream_connect_attempts_per_request{bucket="1"} 29350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1532
telemt_me_reconnect_attempts_total 28493
telemt_me_reconnect_success_total 23873
telemt_me_reader_eof_total 25356
telemt_me_idle_close_by_peer_total 25355
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 423644
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1035082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2198
telemt_desync_full_logged_total 827
telemt_desync_suppressed_total 1371
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 682
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 24271
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23840
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 1034208
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 12242731336 (11.40 GB)
telemt_user_octets_to_client{user="hello"} 313859074872 (292.30 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13731.3 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199117
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2278
telemt_upstream_connect_attempt_total 3979
telemt_upstream_connect_success_total 3978
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 3244
telemt_me_reconnect_success_total 3214
telemt_me_reader_eof_total 3331
telemt_me_idle_close_by_peer_total 3331
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 67006
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175433
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 446
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 293
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3251
telemt_me_writer_restored_same_endpoint_total 3189
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 175395
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 9587494404 (8.93 GB)
telemt_user_octets_to_client{user="hello"} 62193132668 (57.92 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 62
```