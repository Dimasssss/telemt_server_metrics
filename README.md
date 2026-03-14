# Server Metrics 2026-03-14 07:36:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 178664.8 (49h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5041731
telemt_connections_bad_total 40350
telemt_handshake_timeouts_total 114924
telemt_upstream_connect_attempt_total 37532
telemt_upstream_connect_success_total 37288
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 37532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 7348
telemt_me_reconnect_attempts_total 36221
telemt_me_reconnect_success_total 26069
telemt_me_reader_eof_total 27954
telemt_me_idle_close_by_peer_total 27953
telemt_me_route_drop_no_conn_total 1908163
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4624451
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17581
telemt_desync_full_logged_total 4790
telemt_desync_suppressed_total 12791
telemt_desync_frames_bucket_total{bucket="1_2"} 4388
telemt_desync_frames_bucket_total{bucket="3_10"} 6692
telemt_desync_frames_bucket_total{bucket="gt_10"} 6501
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26759
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 26056
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 4625926
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 70521328456 (65.68 GB)
telemt_user_octets_to_client{user="hello"} 1471885482709 (1.34 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78328.4 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 855745
telemt_connections_bad_total 53895
telemt_handshake_timeouts_total 15554
telemt_upstream_connect_attempt_total 21048
telemt_upstream_connect_success_total 20774
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 21047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_keepalive_timeout_total 2146
telemt_me_reconnect_attempts_total 18329
telemt_me_reconnect_success_total 14863
telemt_me_reader_eof_total 15797
telemt_me_idle_close_by_peer_total 15796
telemt_me_route_drop_no_conn_total 282142
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686123
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2040
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1410
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 900
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15183
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14855
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 688038
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 7196389805 (6.70 GB)
telemt_user_octets_to_client{user="hello"} 236114031572 (219.90 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 208285.2 (57h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3610595
telemt_connections_bad_total 42322
telemt_handshake_timeouts_total 237008
telemt_upstream_connect_attempt_total 46998
telemt_upstream_connect_success_total 46977
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10710
telemt_me_reconnect_attempts_total 41279
telemt_me_reconnect_success_total 36301
telemt_me_reader_eof_total 38555
telemt_me_idle_close_by_peer_total 38554
telemt_me_route_drop_no_conn_total 1236228
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3012423
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9918
telemt_desync_full_logged_total 3334
telemt_desync_suppressed_total 6584
telemt_desync_frames_bucket_total{bucket="1_2"} 1741
telemt_desync_frames_bucket_total{bucket="3_10"} 3588
telemt_desync_frames_bucket_total{bucket="gt_10"} 4589
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 36804
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36260
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 3011578
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 50278061000 (46.83 GB)
telemt_user_octets_to_client{user="hello"} 1075407700465 (1001.55 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 208287.6 (57h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2403078
telemt_connections_bad_total 23306
telemt_handshake_timeouts_total 289137
telemt_upstream_connect_attempt_total 65024
telemt_upstream_connect_success_total 62531
telemt_upstream_connect_fail_total 2356
telemt_upstream_connect_attempts_per_request{bucket="1"} 64750
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2355
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20541
telemt_me_reconnect_attempts_total 54225
telemt_me_reconnect_success_total 45144
telemt_me_reader_eof_total 48377
telemt_me_idle_close_by_peer_total 48370
telemt_me_route_drop_no_conn_total 807813
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1892221
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3928
telemt_desync_full_logged_total 1278
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1079
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 184
telemt_me_writer_removed_unexpected_total 45815
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45120
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 671
telemt_user_connections_total{user="hello"} 1898318
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 28506985443 (26.55 GB)
telemt_user_octets_to_client{user="hello"} 695177630798 (647.43 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77721.2 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 828147
telemt_connections_bad_total 8338
telemt_handshake_timeouts_total 9831
telemt_upstream_connect_attempt_total 19885
telemt_upstream_connect_success_total 19351
telemt_upstream_connect_fail_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 19885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 534
telemt_me_keepalive_timeout_total 1590
telemt_me_reconnect_attempts_total 63368
telemt_me_reconnect_success_total 15468
telemt_me_reader_eof_total 17334
telemt_me_idle_close_by_peer_total 17333
telemt_me_route_drop_no_conn_total 319218
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 773766
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1933
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1320
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 735
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17096
telemt_me_refill_failed_total 1492
telemt_me_writer_restored_same_endpoint_total 15463
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1628
telemt_user_connections_total{user="hello"} 773625
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 13739434212 (12.80 GB)
telemt_user_octets_to_client{user="hello"} 260494611772 (242.60 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 82
```