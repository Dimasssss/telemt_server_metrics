# Server Metrics 2026-03-12 08:32:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9248.2 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283595
telemt_connections_bad_total 1314
telemt_handshake_timeouts_total 2001
telemt_upstream_connect_attempt_total 1829
telemt_upstream_connect_success_total 1818
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1317
telemt_me_reconnect_success_total 1309
telemt_me_reader_eof_total 1353
telemt_me_idle_close_by_peer_total 1353
telemt_me_route_drop_no_conn_total 95188
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273888
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1289
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 966
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1315
telemt_me_writer_restored_same_endpoint_total 1296
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 273795
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 4230169212 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 76507314124 (71.25 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38868.7 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210399
telemt_connections_bad_total 2673
telemt_handshake_timeouts_total 7375
telemt_upstream_connect_attempt_total 10059
telemt_upstream_connect_success_total 10053
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 597
telemt_me_reconnect_attempts_total 7948
telemt_me_reconnect_success_total 7906
telemt_me_reader_eof_total 8399
telemt_me_idle_close_by_peer_total 8399
telemt_me_route_drop_no_conn_total 60866
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184081
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 446
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7968
telemt_me_writer_restored_same_endpoint_total 7897
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 184378
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 2764638279 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 71684674230 (66.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 38868.5 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602102
telemt_connections_bad_total 2703
telemt_handshake_timeouts_total 44781
telemt_upstream_connect_attempt_total 10156
telemt_upstream_connect_success_total 10151
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 507
telemt_me_reconnect_attempts_total 7901
telemt_me_reconnect_success_total 7831
telemt_me_reader_eof_total 8219
telemt_me_idle_close_by_peer_total 8219
telemt_me_route_drop_no_conn_total 119703
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345171
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1631
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 1140
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 850
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7825
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7790
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 345441
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 4159986504 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 118951479337 (110.78 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 38869.0 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286900
telemt_connections_bad_total 1805
telemt_handshake_timeouts_total 19301
telemt_upstream_connect_attempt_total 10742
telemt_upstream_connect_success_total 10699
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 8767
telemt_me_reconnect_success_total 8735
telemt_me_reader_eof_total 9277
telemt_me_idle_close_by_peer_total 9277
telemt_me_route_drop_no_conn_total 95554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239154
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 440
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8790
telemt_me_writer_restored_same_endpoint_total 8714
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 238979
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 2802513304 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 82403988828 (76.74 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38868.8 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317356
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 2467
telemt_upstream_connect_attempt_total 12959
telemt_upstream_connect_success_total 12807
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 12959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 560
telemt_me_reconnect_attempts_total 12348
telemt_me_reconnect_success_total 10834
telemt_me_reader_eof_total 11286
telemt_me_idle_close_by_peer_total 11286
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 101377
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299110
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1221
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 813
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 469
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 10980
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10813
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 299052
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 3203239844 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 71603745812 (66.69 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 92
```