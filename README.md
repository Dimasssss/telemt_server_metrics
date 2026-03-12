# Server Metrics 2026-03-12 17:38:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 42000.9 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1517846
telemt_connections_bad_total 20279
telemt_handshake_timeouts_total 14189
telemt_upstream_connect_attempt_total 8284
telemt_upstream_connect_success_total 8236
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 8284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 14943
telemt_me_reconnect_success_total 6099
telemt_me_reader_eof_total 6621
telemt_me_idle_close_by_peer_total 6620
telemt_me_route_drop_no_conn_total 589650
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1422499
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7213
telemt_desync_full_logged_total 1830
telemt_desync_suppressed_total 5383
telemt_desync_frames_bucket_total{bucket="1_2"} 1867
telemt_desync_frames_bucket_total{bucket="3_10"} 2611
telemt_desync_frames_bucket_total{bucket="gt_10"} 2735
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6458
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6086
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 1421996
telemt_user_connections_current{user="hello"} 1773
telemt_user_octets_from_client{user="hello"} 21688743776 (20.20 GB)
telemt_user_octets_to_client{user="hello"} 448850158216 (418.02 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71621.3 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659183
telemt_connections_bad_total 8607
telemt_handshake_timeouts_total 29017
telemt_upstream_connect_attempt_total 17779
telemt_upstream_connect_success_total 17762
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 1354
telemt_me_reconnect_attempts_total 13302
telemt_me_reconnect_success_total 13223
telemt_me_reader_eof_total 14065
telemt_me_idle_close_by_peer_total 14065
telemt_me_route_drop_no_conn_total 205843
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592209
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2473
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 1716
telemt_desync_frames_bucket_total{bucket="1_2"} 1031
telemt_desync_frames_bucket_total{bucket="3_10"} 807
telemt_desync_frames_bucket_total{bucket="gt_10"} 635
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 13361
telemt_me_writer_restored_same_endpoint_total 13214
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 593529
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 9041002743 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 223275959530 (207.94 GB)
telemt_user_msgs_from_client{user="hello"} 4786
telemt_user_msgs_to_client{user="hello"} 14387
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 71621.4 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1372441
telemt_connections_bad_total 6685
telemt_handshake_timeouts_total 97671
telemt_upstream_connect_attempt_total 17066
telemt_upstream_connect_success_total 17061
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1136
telemt_me_reconnect_attempts_total 14347
telemt_me_reconnect_success_total 13109
telemt_me_reader_eof_total 13817
telemt_me_idle_close_by_peer_total 13816
telemt_me_route_drop_no_conn_total 444862
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1038606
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4398
telemt_desync_full_logged_total 1363
telemt_desync_suppressed_total 3035
telemt_desync_frames_bucket_total{bucket="1_2"} 674
telemt_desync_frames_bucket_total{bucket="3_10"} 1606
telemt_desync_frames_bucket_total{bucket="gt_10"} 2118
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13214
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13068
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 1038481
telemt_user_connections_current{user="hello"} 985
telemt_user_octets_from_client{user="hello"} 15571474820 (14.50 GB)
telemt_user_octets_to_client{user="hello"} 362372740549 (337.49 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 71622.0 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829131
telemt_connections_bad_total 9676
telemt_handshake_timeouts_total 63546
telemt_upstream_connect_attempt_total 18716
telemt_upstream_connect_success_total 18644
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 18716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 1583
telemt_me_reconnect_attempts_total 20307
telemt_me_reconnect_success_total 15053
telemt_me_reader_eof_total 16015
telemt_me_idle_close_by_peer_total 16015
telemt_me_route_drop_no_conn_total 290147
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718226
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1605
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1068
telemt_desync_frames_bucket_total{bucket="1_2"} 439
telemt_desync_frames_bucket_total{bucket="3_10"} 620
telemt_desync_frames_bucket_total{bucket="gt_10"} 546
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15334
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 15032
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 717642
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 8840765748 (8.23 GB)
telemt_user_octets_to_client{user="hello"} 291644672444 (271.62 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71621.6 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 934837
telemt_connections_bad_total 11403
telemt_handshake_timeouts_total 7625
telemt_upstream_connect_attempt_total 22837
telemt_upstream_connect_success_total 22565
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 22837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10904
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 1300
telemt_me_reconnect_attempts_total 28863
telemt_me_reconnect_success_total 18957
telemt_me_reader_eof_total 19883
telemt_me_idle_close_by_peer_total 19883
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 343297
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 858410
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3340
telemt_desync_full_logged_total 1146
telemt_desync_suppressed_total 2194
telemt_desync_frames_bucket_total{bucket="1_2"} 906
telemt_desync_frames_bucket_total{bucket="3_10"} 1142
telemt_desync_frames_bucket_total{bucket="gt_10"} 1292
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19477
telemt_me_refill_failed_total 307
telemt_me_writer_restored_same_endpoint_total 18913
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 858292
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 10531342668 (9.81 GB)
telemt_user_octets_to_client{user="hello"} 266116710640 (247.84 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 108
```