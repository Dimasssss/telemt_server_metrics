# Server Metrics 2026-03-10 15:56:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5360.1 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194833
telemt_connections_bad_total 868
telemt_handshake_timeouts_total 945
telemt_upstream_connect_attempt_total 1075
telemt_upstream_connect_success_total 1070
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4841
telemt_me_reconnect_success_total 769
telemt_me_reader_eof_total 852
telemt_me_idle_close_by_peer_total 852
telemt_me_route_drop_no_conn_total 86670
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185295
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 632
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_me_writer_removed_unexpected_total 885
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 185244
telemt_user_connections_current{user="hello"} 1497
telemt_user_octets_from_client{user="hello"} 2394723612 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 51664803144 (48.12 GB)
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 5416.9 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77162
telemt_connections_bad_total 1491
telemt_handshake_timeouts_total 6666
telemt_upstream_connect_attempt_total 1132
telemt_upstream_connect_success_total 1125
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 525
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 837
telemt_me_reconnect_success_total 831
telemt_me_reader_eof_total 839
telemt_me_idle_close_by_peer_total 839
telemt_me_route_drop_no_conn_total 19993
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64401
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 831
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 64389
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 818062684 (780.17 MB)
telemt_user_octets_to_client{user="hello"} 18342171552 (17.08 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 5416.7 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137598
telemt_connections_bad_total 409
telemt_handshake_timeouts_total 7987
telemt_upstream_connect_attempt_total 2311
telemt_upstream_connect_success_total 2271
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 2311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 965
telemt_me_reconnect_success_total 944
telemt_me_reader_eof_total 968
telemt_me_idle_close_by_peer_total 968
telemt_me_route_drop_no_conn_total 44111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115491
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 242
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 961
telemt_me_writer_restored_same_endpoint_total 933
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 116491
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 1252618605 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 33425933373 (31.13 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 5417.3 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89934
telemt_connections_bad_total 5363
telemt_handshake_timeouts_total 8946
telemt_upstream_connect_attempt_total 1175
telemt_upstream_connect_success_total 1175
telemt_upstream_connect_attempts_per_request{bucket="1"} 1175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 512
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 889
telemt_me_reconnect_success_total 885
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_route_drop_no_conn_total 29254
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71379
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 229
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 881
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 71298
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 996713496 (950.54 MB)
telemt_user_octets_to_client{user="hello"} 16985371536 (15.82 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5416.9 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99545
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 787
telemt_upstream_connect_attempt_total 1505
telemt_upstream_connect_success_total 1499
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1208
telemt_me_reconnect_success_total 1200
telemt_me_reader_eof_total 1220
telemt_me_idle_close_by_peer_total 1220
telemt_me_route_drop_no_conn_total 36938
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92154
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 518
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1204
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 92110
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 1569586888 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 26572104228 (24.75 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 113
```