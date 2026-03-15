# Server Metrics 2026-03-15 15:06:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 60702.9 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1926787
telemt_connections_bad_total 103579
telemt_handshake_timeouts_total 22067
telemt_upstream_connect_attempt_total 12120
telemt_upstream_connect_success_total 12068
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13904
telemt_me_reconnect_success_total 9012
telemt_me_reader_eof_total 9635
telemt_me_idle_close_by_peer_total 9635
telemt_me_route_drop_no_conn_total 662214
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1632167
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6216
telemt_desync_full_logged_total 1723
telemt_desync_suppressed_total 4493
telemt_desync_frames_bucket_total{bucket="1_2"} 1537
telemt_desync_frames_bucket_total{bucket="3_10"} 2387
telemt_desync_frames_bucket_total{bucket="gt_10"} 2292
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9311
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9001
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 1631677
telemt_user_connections_current{user="hello"} 2275
telemt_user_octets_from_client{user="hello"} 23647632884 (22.02 GB)
telemt_user_octets_to_client{user="hello"} 633981252964 (590.44 GB)
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 60703.8 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 773255
telemt_connections_bad_total 41562
telemt_handshake_timeouts_total 58591
telemt_upstream_connect_attempt_total 15373
telemt_upstream_connect_success_total 15298
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 15373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11998
telemt_me_reconnect_success_total 11902
telemt_me_reader_eof_total 12573
telemt_me_idle_close_by_peer_total 12573
telemt_me_route_drop_no_conn_total 193519
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586051
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1996
telemt_desync_full_logged_total 691
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12054
telemt_me_writer_restored_same_endpoint_total 11890
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 586297
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 8219077175 (7.65 GB)
telemt_user_octets_to_client{user="hello"} 219671784272 (204.59 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 60703.7 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1700952
telemt_connections_bad_total 47188
telemt_handshake_timeouts_total 170828
telemt_upstream_connect_attempt_total 13376
telemt_upstream_connect_success_total 13312
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 13376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11491
telemt_me_reconnect_success_total 10231
telemt_me_reader_eof_total 10843
telemt_me_idle_close_by_peer_total 10843
telemt_me_route_drop_no_conn_total 453029
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1037272
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2573
telemt_desync_full_logged_total 949
telemt_desync_suppressed_total 1624
telemt_desync_frames_bucket_total{bucket="1_2"} 600
telemt_desync_frames_bucket_total{bucket="3_10"} 997
telemt_desync_frames_bucket_total{bucket="gt_10"} 976
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10413
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10212
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 1033274
telemt_user_connections_current{user="hello"} 1506
telemt_user_octets_from_client{user="hello"} 14995877844 (13.97 GB)
telemt_user_octets_to_client{user="hello"} 371901540200 (346.36 GB)
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 60703.6 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814976
telemt_connections_bad_total 74449
telemt_handshake_timeouts_total 41538
telemt_upstream_connect_attempt_total 167610
telemt_upstream_connect_success_total 167108
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 167610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52425
telemt_me_reconnect_success_total 11986
telemt_me_reader_eof_total 13583
telemt_me_idle_close_by_peer_total 13583
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 178021
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472639
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1258
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 929
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 407
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13367
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 11953
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1381
telemt_user_connections_total{user="hello"} 624557
telemt_user_connections_current{user="hello"} 903
telemt_user_octets_from_client{user="hello"} 11885911906 (11.07 GB)
telemt_user_octets_to_client{user="hello"} 209550182497 (195.16 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 60704.4 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826014
telemt_connections_bad_total 9425
telemt_handshake_timeouts_total 17669
telemt_upstream_connect_attempt_total 13420
telemt_upstream_connect_success_total 13346
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 13420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13971
telemt_me_reconnect_success_total 10290
telemt_me_reader_eof_total 10991
telemt_me_idle_close_by_peer_total 10991
telemt_me_route_drop_no_conn_total 205515
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 676698
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2374
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1572
telemt_desync_frames_bucket_total{bucket="1_2"} 716
telemt_desync_frames_bucket_total{bucket="3_10"} 913
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10524
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10282
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 676742
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 8487872576 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 247702019820 (230.69 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 134
```