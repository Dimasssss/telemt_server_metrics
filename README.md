# Server Metrics 2026-03-12 06:25:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1596.0 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46345
telemt_connections_bad_total 551
telemt_handshake_timeouts_total 307
telemt_upstream_connect_attempt_total 359
telemt_upstream_connect_success_total 357
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 245
telemt_me_reconnect_success_total 244
telemt_me_reader_eof_total 214
telemt_me_idle_close_by_peer_total 214
telemt_me_route_drop_no_conn_total 14619
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44502
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 256
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_restored_same_endpoint_total 231
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 44476
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 1294950744 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 12208009388 (11.37 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31216.6 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125431
telemt_connections_bad_total 1601
telemt_handshake_timeouts_total 4276
telemt_upstream_connect_attempt_total 8275
telemt_upstream_connect_success_total 8270
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 6553
telemt_me_reconnect_success_total 6516
telemt_me_reader_eof_total 6930
telemt_me_idle_close_by_peer_total 6930
telemt_me_route_drop_no_conn_total 37358
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112422
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 333
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 197
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6571
telemt_me_writer_restored_same_endpoint_total 6507
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 112610
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 1717425891 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 47452214582 (44.19 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 31216.6 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454713
telemt_connections_bad_total 2276
telemt_handshake_timeouts_total 33171
telemt_upstream_connect_attempt_total 8571
telemt_upstream_connect_success_total 8569
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6707
telemt_me_reconnect_success_total 6643
telemt_me_reader_eof_total 6960
telemt_me_idle_close_by_peer_total 6960
telemt_me_route_drop_no_conn_total 70581
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212493
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 899
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 605
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 451
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6625
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6602
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 212799
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 2222897300 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 64941282789 (60.48 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 31216.8 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184458
telemt_connections_bad_total 1729
telemt_handshake_timeouts_total 12295
telemt_upstream_connect_attempt_total 9009
telemt_upstream_connect_success_total 8970
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 7429
telemt_me_reconnect_success_total 7401
telemt_me_reader_eof_total 7858
telemt_me_idle_close_by_peer_total 7858
telemt_me_route_drop_no_conn_total 60370
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156229
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 233
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7444
telemt_me_writer_restored_same_endpoint_total 7380
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 156096
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 1812615828 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 47622722828 (44.35 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31216.6 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202617
telemt_connections_bad_total 308
telemt_handshake_timeouts_total 1238
telemt_upstream_connect_attempt_total 10774
telemt_upstream_connect_success_total 10653
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 10774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 10584
telemt_me_reconnect_success_total 9074
telemt_me_reader_eof_total 9458
telemt_me_idle_close_by_peer_total 9458
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 62092
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193216
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 723
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 478
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 9205
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9055
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 193170
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 1711007392 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 44429331748 (41.38 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 77
```