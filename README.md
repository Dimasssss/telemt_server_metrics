# Server Metrics 2026-03-12 11:00:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18116.3 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606629
telemt_connections_bad_total 1486
telemt_handshake_timeouts_total 3602
telemt_upstream_connect_attempt_total 3477
telemt_upstream_connect_success_total 3455
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 308
telemt_me_reconnect_attempts_total 6384
telemt_me_reconnect_success_total 2495
telemt_me_reader_eof_total 2704
telemt_me_idle_close_by_peer_total 2704
telemt_me_route_drop_no_conn_total 209081
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584069
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2850
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 2137
telemt_desync_frames_bucket_total{bucket="1_2"} 718
telemt_desync_frames_bucket_total{bucket="3_10"} 1053
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2642
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2482
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 583927
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 10438001880 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 159116510572 (148.19 GB)
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47736.4 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325059
telemt_connections_bad_total 3507
telemt_handshake_timeouts_total 10242
telemt_upstream_connect_attempt_total 11882
telemt_upstream_connect_success_total 11876
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 679
telemt_me_reconnect_attempts_total 9364
telemt_me_reconnect_success_total 9313
telemt_me_reader_eof_total 9900
telemt_me_idle_close_by_peer_total 9900
telemt_me_route_drop_no_conn_total 93911
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291583
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 255
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9395
telemt_me_writer_restored_same_endpoint_total 9304
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 292016
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 4019107095 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 105465017622 (98.22 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 47736.4 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793223
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 57985
telemt_upstream_connect_attempt_total 11855
telemt_upstream_connect_success_total 11850
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 593
telemt_me_reconnect_attempts_total 9205
telemt_me_reconnect_success_total 9128
telemt_me_reader_eof_total 9595
telemt_me_idle_close_by_peer_total 9595
telemt_me_route_drop_no_conn_total 181892
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516944
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2334
telemt_desync_full_logged_total 691
telemt_desync_suppressed_total 1643
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 798
telemt_desync_frames_bucket_total{bucket="gt_10"} 1237
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9145
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9087
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 517194
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 6685449168 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 165270713781 (153.92 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 47736.8 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415724
telemt_connections_bad_total 2489
telemt_handshake_timeouts_total 33800
telemt_upstream_connect_attempt_total 12732
telemt_upstream_connect_success_total 12681
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 12732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 855
telemt_me_reconnect_attempts_total 10350
telemt_me_reconnect_success_total 10310
telemt_me_reader_eof_total 10939
telemt_me_idle_close_by_peer_total 10939
telemt_me_route_drop_no_conn_total 139041
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350226
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 711
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 461
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 298
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10381
telemt_me_writer_restored_same_endpoint_total 10289
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 350046
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 4125794916 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 134027373600 (124.82 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47736.5 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471608
telemt_connections_bad_total 477
telemt_handshake_timeouts_total 3544
telemt_upstream_connect_attempt_total 15313
telemt_upstream_connect_success_total 15133
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 15313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 641
telemt_me_reconnect_attempts_total 14279
telemt_me_reconnect_success_total 12754
telemt_me_reader_eof_total 13268
telemt_me_idle_close_by_peer_total 13268
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 153425
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443714
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1839
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1227
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12925
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12729
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 443643
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 4969897544 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 108075229564 (100.65 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 167
```