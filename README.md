# Server Metrics 2026-03-12 18:19:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 44454.2 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1595807
telemt_connections_bad_total 20489
telemt_handshake_timeouts_total 14861
telemt_upstream_connect_attempt_total 8894
telemt_upstream_connect_success_total 8843
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 535
telemt_me_reconnect_attempts_total 15414
telemt_me_reconnect_success_total 6569
telemt_me_reader_eof_total 7116
telemt_me_idle_close_by_peer_total 7115
telemt_me_route_drop_no_conn_total 623307
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1494580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7647
telemt_desync_full_logged_total 1944
telemt_desync_suppressed_total 5703
telemt_desync_frames_bucket_total{bucket="1_2"} 1982
telemt_desync_frames_bucket_total{bucket="3_10"} 2781
telemt_desync_frames_bucket_total{bucket="gt_10"} 2884
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6937
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6556
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 1494074
telemt_user_connections_current{user="hello"} 1557
telemt_user_octets_from_client{user="hello"} 23065329884 (21.48 GB)
telemt_user_octets_to_client{user="hello"} 494572551100 (460.61 GB)
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74074.6 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688452
telemt_connections_bad_total 8936
telemt_handshake_timeouts_total 29305
telemt_upstream_connect_attempt_total 19065
telemt_upstream_connect_success_total 19036
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3357
telemt_me_reconnect_attempts_total 13741
telemt_me_reconnect_success_total 13656
telemt_me_reader_eof_total 14515
telemt_me_idle_close_by_peer_total 14515
telemt_me_route_drop_no_conn_total 219478
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619439
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2713
telemt_desync_full_logged_total 827
telemt_desync_suppressed_total 1886
telemt_desync_frames_bucket_total{bucket="1_2"} 1100
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 721
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13798
telemt_me_writer_restored_same_endpoint_total 13647
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 621319
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 9430007808 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 233289608143 (217.27 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 74074.7 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1427640
telemt_connections_bad_total 6982
telemt_handshake_timeouts_total 99887
telemt_upstream_connect_attempt_total 17639
telemt_upstream_connect_success_total 17634
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1162
telemt_me_reconnect_attempts_total 14783
telemt_me_reconnect_success_total 13539
telemt_me_reader_eof_total 14268
telemt_me_idle_close_by_peer_total 14267
telemt_me_route_drop_no_conn_total 468212
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1088710
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4597
telemt_desync_full_logged_total 1422
telemt_desync_suppressed_total 3175
telemt_desync_frames_bucket_total{bucket="1_2"} 716
telemt_desync_frames_bucket_total{bucket="3_10"} 1670
telemt_desync_frames_bucket_total{bucket="gt_10"} 2211
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13655
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13498
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 1088579
telemt_user_connections_current{user="hello"} 1012
telemt_user_octets_from_client{user="hello"} 16366859956 (15.24 GB)
telemt_user_octets_to_client{user="hello"} 395240112965 (368.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 74075.3 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868133
telemt_connections_bad_total 11561
telemt_handshake_timeouts_total 64954
telemt_upstream_connect_attempt_total 19286
telemt_upstream_connect_success_total 19210
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 19286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1617
telemt_me_reconnect_attempts_total 23205
telemt_me_reconnect_success_total 15482
telemt_me_reader_eof_total 16538
telemt_me_idle_close_by_peer_total 16538
telemt_me_route_drop_no_conn_total 304089
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750719
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1729
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 1151
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 15847
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15461
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 750133
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 9166297316 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 303189746988 (282.37 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74075.0 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 973643
telemt_connections_bad_total 11411
telemt_handshake_timeouts_total 8033
telemt_upstream_connect_attempt_total 23434
telemt_upstream_connect_success_total 23155
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 23434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 1346
telemt_me_reconnect_attempts_total 30443
telemt_me_reconnect_success_total 19409
telemt_me_reader_eof_total 20402
telemt_me_idle_close_by_peer_total 20402
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 361413
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 893948
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3444
telemt_desync_full_logged_total 1191
telemt_desync_suppressed_total 2253
telemt_desync_frames_bucket_total{bucket="1_2"} 963
telemt_desync_frames_bucket_total{bucket="3_10"} 1161
telemt_desync_frames_bucket_total{bucket="gt_10"} 1320
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 19973
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19365
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 893826
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 11019678080 (10.26 GB)
telemt_user_octets_to_client{user="hello"} 289189501820 (269.33 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 99
```