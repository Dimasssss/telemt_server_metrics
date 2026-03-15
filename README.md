# Server Metrics 2026-03-15 17:34:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 69593.8 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2439652
telemt_connections_bad_total 148571
telemt_handshake_timeouts_total 31331
telemt_upstream_connect_attempt_total 13569
telemt_upstream_connect_success_total 13510
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 14912
telemt_me_reconnect_success_total 10015
telemt_me_reader_eof_total 10706
telemt_me_idle_close_by_peer_total 10706
telemt_me_route_drop_no_conn_total 840664
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2035767
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7954
telemt_desync_full_logged_total 2157
telemt_desync_suppressed_total 5797
telemt_desync_frames_bucket_total{bucket="1_2"} 1929
telemt_desync_frames_bucket_total{bucket="3_10"} 3059
telemt_desync_frames_bucket_total{bucket="gt_10"} 2966
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10336
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10004
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 2035263
telemt_user_connections_current{user="hello"} 2381
telemt_user_octets_from_client{user="hello"} 30109145160 (28.04 GB)
telemt_user_octets_to_client{user="hello"} 772087500856 (719.06 GB)
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 69594.7 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 941884
telemt_connections_bad_total 50715
telemt_handshake_timeouts_total 62242
telemt_upstream_connect_attempt_total 17443
telemt_upstream_connect_success_total 17349
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 17443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14703
telemt_me_reconnect_success_total 13495
telemt_me_reader_eof_total 14277
telemt_me_idle_close_by_peer_total 14277
telemt_me_route_drop_no_conn_total 243469
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728748
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2188
telemt_desync_full_logged_total 735
telemt_desync_suppressed_total 1453
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13708
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13483
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 728982
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 10633018287 (9.90 GB)
telemt_user_octets_to_client{user="hello"} 275100932224 (256.21 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 69594.7 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2103231
telemt_connections_bad_total 49892
telemt_handshake_timeouts_total 213436
telemt_upstream_connect_attempt_total 15091
telemt_upstream_connect_success_total 15018
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 15091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12760
telemt_me_reconnect_success_total 11491
telemt_me_reader_eof_total 12176
telemt_me_idle_close_by_peer_total 12176
telemt_me_route_drop_no_conn_total 544700
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1298123
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3319
telemt_desync_full_logged_total 1202
telemt_desync_suppressed_total 2117
telemt_desync_frames_bucket_total{bucket="1_2"} 756
telemt_desync_frames_bucket_total{bucket="3_10"} 1289
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11693
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11472
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 1294050
telemt_user_connections_current{user="hello"} 1435
telemt_user_octets_from_client{user="hello"} 21894638348 (20.39 GB)
telemt_user_octets_to_client{user="hello"} 465968747604 (433.97 GB)
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 69594.4 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1010853
telemt_connections_bad_total 82046
telemt_handshake_timeouts_total 49081
telemt_upstream_connect_attempt_total 170463
telemt_upstream_connect_success_total 169879
telemt_upstream_connect_fail_total 584
telemt_upstream_connect_attempts_per_request{bucket="1"} 170463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 584
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61476
telemt_me_reconnect_success_total 13412
telemt_me_reader_eof_total 15273
telemt_me_idle_close_by_peer_total 15273
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 236192
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629349
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1790
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 15056
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13376
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1644
telemt_user_connections_total{user="hello"} 781869
telemt_user_connections_current{user="hello"} 944
telemt_user_octets_from_client{user="hello"} 14506084089 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 279288603608 (260.11 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 69595.3 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021965
telemt_connections_bad_total 12073
telemt_handshake_timeouts_total 22946
telemt_upstream_connect_attempt_total 15381
telemt_upstream_connect_success_total 15298
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15488
telemt_me_reconnect_success_total 11792
telemt_me_reader_eof_total 12581
telemt_me_idle_close_by_peer_total 12581
telemt_me_route_drop_no_conn_total 254614
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 845836
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2842
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 1885
telemt_desync_frames_bucket_total{bucket="1_2"} 873
telemt_desync_frames_bucket_total{bucket="3_10"} 1060
telemt_desync_frames_bucket_total{bucket="gt_10"} 909
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12051
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11784
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 845865
telemt_user_connections_current{user="hello"} 1006
telemt_user_octets_from_client{user="hello"} 10552223392 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 297733320368 (277.29 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 125
```