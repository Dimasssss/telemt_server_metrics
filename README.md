# Server Metrics 2026-03-12 13:13:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26074.1 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901801
telemt_connections_bad_total 5203
telemt_handshake_timeouts_total 8035
telemt_upstream_connect_attempt_total 5101
telemt_upstream_connect_success_total 5070
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 7645
telemt_me_reconnect_success_total 3747
telemt_me_reader_eof_total 4018
telemt_me_idle_close_by_peer_total 4017
telemt_me_route_drop_no_conn_total 320438
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 862769
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4626
telemt_desync_full_logged_total 1166
telemt_desync_suppressed_total 3460
telemt_desync_frames_bucket_total{bucket="1_2"} 1161
telemt_desync_frames_bucket_total{bucket="3_10"} 1682
telemt_desync_frames_bucket_total{bucket="gt_10"} 1783
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3910
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3734
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 862589
telemt_user_connections_current{user="hello"} 1686
telemt_user_octets_from_client{user="hello"} 14411947080 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 256192949612 (238.60 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55694.6 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445319
telemt_connections_bad_total 5283
telemt_handshake_timeouts_total 24434
telemt_upstream_connect_attempt_total 13471
telemt_upstream_connect_success_total 13464
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1069
telemt_me_reconnect_attempts_total 10573
telemt_me_reconnect_success_total 10515
telemt_me_reader_eof_total 11177
telemt_me_idle_close_by_peer_total 11177
telemt_me_route_drop_no_conn_total 127971
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1336
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 903
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 334
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10611
telemt_me_writer_restored_same_endpoint_total 10506
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 393329
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 5874785711 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 142247107922 (132.48 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 55694.6 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985215
telemt_connections_bad_total 5428
telemt_handshake_timeouts_total 74493
telemt_upstream_connect_attempt_total 13443
telemt_upstream_connect_success_total 13438
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 866
telemt_me_reconnect_attempts_total 10403
telemt_me_reconnect_success_total 10312
telemt_me_reader_eof_total 10862
telemt_me_idle_close_by_peer_total 10862
telemt_me_route_drop_no_conn_total 247514
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687367
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3036
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 2120
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 1090
telemt_desync_frames_bucket_total{bucket="gt_10"} 1514
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10343
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10271
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 687588
telemt_user_connections_current{user="hello"} 1029
telemt_user_octets_from_client{user="hello"} 9120570752 (8.49 GB)
telemt_user_octets_to_client{user="hello"} 219522330153 (204.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 55695.0 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557485
telemt_connections_bad_total 7644
telemt_handshake_timeouts_total 52261
telemt_upstream_connect_attempt_total 14874
telemt_upstream_connect_success_total 14814
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 14874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1273
telemt_me_reconnect_attempts_total 13275
telemt_me_reconnect_success_total 12043
telemt_me_reader_eof_total 12777
telemt_me_idle_close_by_peer_total 12777
telemt_me_route_drop_no_conn_total 187181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466955
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 947
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 616
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 390
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12173
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12022
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 466464
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 5267425780 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 187835011616 (174.93 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55694.8 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628091
telemt_connections_bad_total 1734
telemt_handshake_timeouts_total 5134
telemt_upstream_connect_attempt_total 17798
telemt_upstream_connect_success_total 17583
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 17798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 973
telemt_me_reconnect_attempts_total 22031
telemt_me_reconnect_success_total 14805
telemt_me_reader_eof_total 15520
telemt_me_idle_close_by_peer_total 15520
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 213808
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585560
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2450
telemt_desync_full_logged_total 827
telemt_desync_suppressed_total 1623
telemt_desync_frames_bucket_total{bucket="1_2"} 679
telemt_desync_frames_bucket_total{bucket="3_10"} 868
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 15175
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14778
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 585471
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 6773868772 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 154417381932 (143.81 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 122
```