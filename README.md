# Server Metrics 2026-03-12 23:25:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 62834.1 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1953851
telemt_connections_bad_total 26079
telemt_handshake_timeouts_total 21218
telemt_upstream_connect_attempt_total 12448
telemt_upstream_connect_success_total 12377
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 12448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 618
telemt_me_reconnect_attempts_total 18087
telemt_me_reconnect_success_total 9231
telemt_me_reader_eof_total 9967
telemt_me_idle_close_by_peer_total 9966
telemt_me_route_drop_no_conn_total 760989
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1816780
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8568
telemt_desync_full_logged_total 2235
telemt_desync_suppressed_total 6333
telemt_desync_frames_bucket_total{bucket="1_2"} 2262
telemt_desync_frames_bucket_total{bucket="3_10"} 3081
telemt_desync_frames_bucket_total{bucket="gt_10"} 3225
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9639
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9218
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 1816248
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 27248798888 (25.38 GB)
telemt_user_octets_to_client{user="hello"} 644026471740 (599.80 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92454.7 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 807824
telemt_connections_bad_total 11735
telemt_handshake_timeouts_total 31497
telemt_upstream_connect_attempt_total 23400
telemt_upstream_connect_success_total 23371
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3423
telemt_me_reconnect_attempts_total 17213
telemt_me_reconnect_success_total 17117
telemt_me_reader_eof_total 18218
telemt_me_idle_close_by_peer_total 18218
telemt_me_route_drop_no_conn_total 261215
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730452
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3016
telemt_desync_full_logged_total 940
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 1199
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17289
telemt_me_writer_restored_same_endpoint_total 17108
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 732332
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 12123553516 (11.29 GB)
telemt_user_octets_to_client{user="hello"} 283197788887 (263.75 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 92454.5 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1681990
telemt_connections_bad_total 8095
telemt_handshake_timeouts_total 113364
telemt_upstream_connect_attempt_total 21461
telemt_upstream_connect_success_total 21455
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1227
telemt_me_reconnect_attempts_total 17743
telemt_me_reconnect_success_total 16492
telemt_me_reader_eof_total 17438
telemt_me_idle_close_by_peer_total 17437
telemt_me_route_drop_no_conn_total 551599
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1314698
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4974
telemt_desync_full_logged_total 1526
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2383
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16652
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16451
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 1314304
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 19796266788 (18.44 GB)
telemt_user_octets_to_client{user="hello"} 484722456789 (451.43 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 92454.8 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1039525
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 71545
telemt_upstream_connect_attempt_total 32693
telemt_upstream_connect_success_total 30434
telemt_upstream_connect_fail_total 2122
telemt_upstream_connect_attempts_per_request{bucket="1"} 32419
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2121
telemt_me_keepalive_timeout_total 11247
telemt_me_reconnect_attempts_total 27798
telemt_me_reconnect_success_total 19961
telemt_me_reader_eof_total 21613
telemt_me_idle_close_by_peer_total 21606
telemt_me_route_drop_no_conn_total 368974
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 900190
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 20323
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 19939
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 905410
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 14291852869 (13.31 GB)
telemt_user_octets_to_client{user="hello"} 360763148206 (335.99 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92454.8 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158342
telemt_connections_bad_total 12542
telemt_handshake_timeouts_total 9264
telemt_upstream_connect_attempt_total 28127
telemt_upstream_connect_success_total 27778
telemt_upstream_connect_fail_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 28127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 1459
telemt_me_reconnect_attempts_total 34205
telemt_me_reconnect_success_total 23165
telemt_me_reader_eof_total 24367
telemt_me_idle_close_by_peer_total 24367
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 432772
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1067654
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4021
telemt_desync_full_logged_total 1404
telemt_desync_suppressed_total 2617
telemt_desync_frames_bucket_total{bucket="1_2"} 1169
telemt_desync_frames_bucket_total{bucket="3_10"} 1338
telemt_desync_frames_bucket_total{bucket="gt_10"} 1514
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 23781
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23120
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 1067512
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 13519204784 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 376316602216 (350.47 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 41
```