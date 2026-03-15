# Server Metrics 2026-03-15 14:10:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 57331.0 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1755191
telemt_connections_bad_total 97198
telemt_handshake_timeouts_total 18816
telemt_upstream_connect_attempt_total 11394
telemt_upstream_connect_success_total 11345
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13358
telemt_me_reconnect_success_total 8470
telemt_me_reader_eof_total 9070
telemt_me_idle_close_by_peer_total 9070
telemt_me_route_drop_no_conn_total 600260
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1482647
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5555
telemt_desync_full_logged_total 1546
telemt_desync_suppressed_total 4009
telemt_desync_frames_bucket_total{bucket="1_2"} 1418
telemt_desync_frames_bucket_total{bucket="3_10"} 2157
telemt_desync_frames_bucket_total{bucket="gt_10"} 1980
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8756
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8459
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 1482274
telemt_user_connections_current{user="hello"} 2276
telemt_user_octets_from_client{user="hello"} 21142568864 (19.69 GB)
telemt_user_octets_to_client{user="hello"} 583301862864 (543.24 GB)
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 57331.5 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 713025
telemt_connections_bad_total 38790
telemt_handshake_timeouts_total 57010
telemt_upstream_connect_attempt_total 14678
telemt_upstream_connect_success_total 14607
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 14678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11484
telemt_me_reconnect_success_total 11393
telemt_me_reader_eof_total 12044
telemt_me_idle_close_by_peer_total 12044
telemt_me_route_drop_no_conn_total 176798
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534421
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1973
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1292
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11534
telemt_me_writer_restored_same_endpoint_total 11381
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 534682
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 7552485511 (7.03 GB)
telemt_user_octets_to_client{user="hello"} 201270680804 (187.45 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 57331.5 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1513762
telemt_connections_bad_total 44865
telemt_handshake_timeouts_total 158347
telemt_upstream_connect_attempt_total 12651
telemt_upstream_connect_success_total 12593
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 12651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10954
telemt_me_reconnect_success_total 9700
telemt_me_reader_eof_total 10282
telemt_me_idle_close_by_peer_total 10282
telemt_me_route_drop_no_conn_total 419597
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 944679
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2404
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 1518
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 919
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9869
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9681
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 940786
telemt_user_connections_current{user="hello"} 1206
telemt_user_octets_from_client{user="hello"} 13655125784 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 340840189580 (317.43 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 57331.5 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 729038
telemt_connections_bad_total 71221
telemt_handshake_timeouts_total 39316
telemt_upstream_connect_attempt_total 121154
telemt_upstream_connect_success_total 120692
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 121153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 49507
telemt_me_reconnect_success_total 11794
telemt_me_reader_eof_total 13304
telemt_me_idle_close_by_peer_total 13304
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 170278
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445834
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1172
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13083
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 11762
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1289
telemt_user_connections_total{user="hello"} 551729
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 10096343601 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 188113555448 (175.19 GB)
telemt_user_msgs_from_client{user="hello"} 2048522
telemt_user_msgs_to_client{user="hello"} 7672045
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 57332.3 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754614
telemt_connections_bad_total 9247
telemt_handshake_timeouts_total 15767
telemt_upstream_connect_attempt_total 12639
telemt_upstream_connect_success_total 12571
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13373
telemt_me_reconnect_success_total 9698
telemt_me_reader_eof_total 10373
telemt_me_idle_close_by_peer_total 10373
telemt_me_route_drop_no_conn_total 187018
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612042
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2252
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1498
telemt_desync_frames_bucket_total{bucket="1_2"} 674
telemt_desync_frames_bucket_total{bucket="3_10"} 878
telemt_desync_frames_bucket_total{bucket="gt_10"} 700
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9928
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9690
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 612082
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 7582205352 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 229771587136 (213.99 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 117
```