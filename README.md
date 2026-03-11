# Server Metrics 2026-03-11 09:40:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 69179.0 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1480783
telemt_connections_bad_total 19589
telemt_handshake_timeouts_total 40719
telemt_upstream_connect_attempt_total 14356
telemt_upstream_connect_success_total 14347
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 780
telemt_me_reconnect_attempts_total 22555
telemt_me_reconnect_success_total 10867
telemt_me_reader_eof_total 11774
telemt_me_idle_close_by_peer_total 11774
telemt_me_route_drop_no_conn_total 546871
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1345190
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6603
telemt_desync_full_logged_total 1830
telemt_desync_suppressed_total 4773
telemt_desync_frames_bucket_total{bucket="1_2"} 1738
telemt_desync_frames_bucket_total{bucket="3_10"} 2517
telemt_desync_frames_bucket_total{bucket="gt_10"} 2348
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11338
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10861
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 1343768
telemt_user_connections_current{user="hello"} 1402
telemt_user_octets_from_client{user="hello"} 17687652376 (16.47 GB)
telemt_user_octets_to_client{user="hello"} 386436915612 (359.90 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69235.8 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568514
telemt_connections_bad_total 10011
telemt_handshake_timeouts_total 31154
telemt_upstream_connect_attempt_total 23334
telemt_upstream_connect_success_total 20405
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2107
telemt_me_reconnect_attempts_total 14846
telemt_me_reconnect_success_total 14008
telemt_me_reader_eof_total 14831
telemt_me_idle_close_by_peer_total 14829
telemt_me_route_drop_no_conn_total 236801
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482400
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2224
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1541
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 795
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 14173
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13986
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 484637
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 4715390098 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 133193902488 (124.05 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 69235.7 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992348
telemt_connections_bad_total 7559
telemt_handshake_timeouts_total 97708
telemt_upstream_connect_attempt_total 18668
telemt_upstream_connect_success_total 18441
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 18668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 26278
telemt_me_reconnect_success_total 13911
telemt_me_reader_eof_total 14949
telemt_me_idle_close_by_peer_total 14949
telemt_me_route_drop_no_conn_total 325717
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848077
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2424
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1707
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 887
telemt_desync_frames_bucket_total{bucket="gt_10"} 957
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14481
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13900
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 848963
telemt_user_connections_current{user="hello"} 838
telemt_user_octets_from_client{user="hello"} 10058526205 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 258219770281 (240.49 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 69236.1 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723402
telemt_connections_bad_total 65087
telemt_handshake_timeouts_total 69832
telemt_upstream_connect_attempt_total 18990
telemt_upstream_connect_success_total 18990
telemt_upstream_connect_attempts_per_request{bucket="1"} 18990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 712
telemt_me_reconnect_attempts_total 16602
telemt_me_reconnect_success_total 15548
telemt_me_reader_eof_total 16513
telemt_me_idle_close_by_peer_total 16512
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 226203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566480
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1262
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 786
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 15732
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15525
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 565856
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 6589839432 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 161097893528 (150.03 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69235.8 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768051
telemt_connections_bad_total 5984
telemt_handshake_timeouts_total 7251
telemt_upstream_connect_attempt_total 18740
telemt_upstream_connect_success_total 18666
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 768
telemt_me_reconnect_attempts_total 18898
telemt_me_reconnect_success_total 15106
telemt_me_reader_eof_total 15965
telemt_me_idle_close_by_peer_total 15965
telemt_me_route_drop_no_conn_total 263297
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 696065
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2961
telemt_desync_full_logged_total 1119
telemt_desync_suppressed_total 1842
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1212
telemt_desync_frames_bucket_total{bucket="gt_10"} 714
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15417
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15106
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 695748
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 10970810579 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 251734879170 (234.45 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 104
```